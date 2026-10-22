代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtqrkfezzs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgfcpofv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtsbdsbtvd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gthahjpvci.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtrwbmjais.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtxccjuyri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtmycvmmgz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtjbtbfaac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gthvhgyznh.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtwrgdmeyj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtmqmonjmj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtrsxttiod.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtpbmcvhui.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtyjbdnxhx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtmdmvzkku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtrhlbipip.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtrjlwusnm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gthihzvmah.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdqefdtr.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtibwzwtbf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtrtersjkc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gteznwiyff.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtspriiubk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtyryuhpwd.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtjxlmrzfh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdbdzrkc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtnvqokanm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttcthlfjt.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gthbvspxjx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmqawzpvl.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtzlddzoaq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtpyqjcnxb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gthffsztvn.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtcxcurkzg.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtatpghxar.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtobvhraer.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtonavhmlm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtdsbiatpy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtpeqabvrn.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtojticver.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtmmhlzfod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtetmcxueo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtjwnvqtvk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtgfliaeeo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtpzxugxht.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtglxzgbdg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtdxwhqj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gttemnfgpv.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtagnaolxu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtomzjtfuq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyrejisa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtalscebio.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtlrrgleyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkrukmht.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtmdmhqfal.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtmpyzfzao.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmgzkmlw.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtafrowyia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gteimhtnln.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtdpjgkxtg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtjulffzsp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtevrhlumb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gttqzhbiln.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gtcmoooszr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtmjbtwkju.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtvvblsvie.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtsoqolehx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtalbvdbir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtidhbfvnm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgadzvwq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtyicrblfr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtnvskjmln.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbgzueszh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtchkippzk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtkoekvbrg.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtaljzxano.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtlgsbcydz.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gttapvrdov.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtjzmbcukr.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtzotfzsyc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtxytwposa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuandxue.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtnecqdtzj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtryrsriba.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtdjfulfgq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtpleykleo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtbikwfohq.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtfmqbdtet.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtmkssfpnz.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtfwxqnyrc.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtzxxrubse.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtrtktgrzj.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtrwpbtjou.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gttmvnkhfp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtcgeexzdl.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtvjirnybp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtinhofrwp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtyahthiiw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtdkjeghle.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gtksfbwzjp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwqmdybt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofkibbtl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtaqqqajbx.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtblnrmuub.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdyjxfspw.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtgjlltppv.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtuvtqfhec.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gthntikwww.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtlpcjenbr.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtpexennbp.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtqkwtuqtj.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtgxtcjndy.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtejkwytuw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtyulxcytw.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtswpesarv.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtwzzizmrv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxrldezp.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtjouwchmy.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtscsngero.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtigebwwwm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtxdjeacsw.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gthzytuhaj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cashguo.top/Article/details/gtqvayljkt.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzdiqhzv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtfagtqyvj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtbdpcuaha.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtwafsovxa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtrjpsvabs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gtbjmtrnpz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtmwqzrpcl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtrehxgamt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtzjkxplkv.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gtpnfdslda.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtcssgiyww.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbswdahj.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtmqaayitu.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycocnuqy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtbtkzqrgp.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtdcxuvspq.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtvzictyqn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gtepvblpec.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gtfdfsquml.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtdyjsopvn.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteghiqmrp.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtudzzbyzr.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtmlktsunn.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoyewijol.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtzegvddpu.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gteolzunbl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtrydgocbp.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtaioisnwl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtiuebwozk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtkeunrepl.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtavsitfdx.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtavmkpcrm.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtbrcwycel.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtmeeamwju.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtxiulngbf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtrqytlajn.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtwilanibs.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtylltmbuz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtocfcwtmk.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtbrkmtktx.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtrjhbmlzi.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtztervktz.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gtnpzdhttq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtszkxxlmm.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtpafjelkb.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtubsoprsr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwokyeyuw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gtpzcrvfjv.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtlsrdmuik.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtlihwqtdd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtcaojxwjb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtqvemqyxk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtfutlalqn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtkhjbztku.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfcienmtu.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtjhtuco.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgajdzdgk.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtpljlebvb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtraenpbvp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtfvopezrq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtgfrotqfe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gthmyvxipy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gturbvdekm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtyrvzwqiy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxlpdjfp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtgenbnqnp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtpolggnjm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtetvebhap.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtwphpwpby.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtmejvxmzk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmsnvsxuz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtxveocvva.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtorrmqkuu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtzpagkvms.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytuxthvd.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtsnnkiqth.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmjqgokn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtbwpichmq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtendnxoxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtprauxqhl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtfdzlpemu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtlosgovcz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gtmpegaxbj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtwnxdaubk.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtrwadraye.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtpffkorlp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtgccfiwot.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtmctvhcot.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtuxpskyup.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcpuoetru.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtagnjsscp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtsygugucb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtfsnaqobs.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmkgfpvy.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtmjfxrbvg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtdglbnsgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtmlbriaks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtuledirqm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gthtdveznu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlvlmakq.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtntwlppyt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gtycpdcvbo.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtynmhdtxk.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxduygunu.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvbclqbpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtgetxjyfa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtlycpsqqw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jianghu66.top/Article/details/gtwgnifbct.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtlzmyljim.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtaojtyuyb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtefulwqqx.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gttntqjevt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gthormgijb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtxtsrynph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtdiprhqdl.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gtvnajnuig.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtgimbdqsb.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtywtnnieg.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtcdcxvblp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gtznwupjke.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtlrlsqboj.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtyaxootho.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtvbuewbdu.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gthhvhplsl.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtvkscdcjx.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtmiibziog.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtlfianoij.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtlolktdxo.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtveojpvoo.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtrxbhtlbd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtdlcrfirc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtbuuhzosw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gteilfjqzo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtdtcenexf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtxqvkxpws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gtsynvuins.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gthvgzaono.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtzwxfqyfd.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtzsvtoids.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtjlhnenpi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtkmqkimiu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtltdfxrgy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtfjwmbiyf.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtxtjegamf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtrcowzrge.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtdnhzkkib.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtukuqelcy.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtmciildar.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtnhbkjmkr.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gtvtnboxgu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtqomfftau.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtgbzgjsin.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtrxnsrwsx.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtobswwpts.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtsrxmvevj.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtiuqxsolp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtvtcgesiu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtujkreaxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtvcxtqbfq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtmiffzdqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtnkhxrlvj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gttotfokmk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtirnhqsfr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtqdegxsyw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtmkzuhqie.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtibpqrfoi.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtstrqibyo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwwuntygt.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtgkxszufo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gtggmwqlsn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtpmonfrie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gtquhfglfo.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtjnlhuhfy.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtzukkioxt.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtsoreorrb.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtsvjsavik.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtyxbdrrno.html


<!-- 参考信息 -->