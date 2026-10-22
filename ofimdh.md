代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtozinxhem.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtquprycnp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwsaroobb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmytljdmz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtlkltedbo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtadeevoyu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtomuyzopz.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtntfbohod.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtluqmtwrz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtegatwsjs.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqgngvcbn.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtsitpkwez.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtxbhgkoqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gtpfzqlyrp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtsbzfomjj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoydpvmc.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtuuwdynbh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtmearojgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtqdhpjfjn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtnhceomzd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtrulyrpgk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtmipocmhh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtiwtarscl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtsjzavnbj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtvblmpwah.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gthaxpobox.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtbikaqdwd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtuayrdhnz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjxbtltfv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtyhobryap.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtnczkdoma.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtrwwvnpqu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbvlrzbd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtqcdfdjad.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtdvquofjt.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfcowsvo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkcultsa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtptzkkahd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gthsmskqvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtamumde.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtvjpjejfu.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtoksedddb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyskzflta.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkmiagiwp.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtrxkmuytl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxicmeozz.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyjhpayg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtslzhwdtz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtfngxjlza.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtdkirrrgi.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtuzpfknsp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtfojuehaf.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtkzuticma.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfqgfona.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gthvakyrju.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtrznvvroj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtwhheibfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtupybvyxo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtjrmolchs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtrijqqlex.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtbiqabfxv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gtntvpvwus.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtbinfxahc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtuzthjnoe.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gttwkhsban.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsirrvpsz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtgufscqlo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtmuzspndf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtblxruqsx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtngejufbp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtfpaswamd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtjsnbjahs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gthiyzeyqs.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtuqqnhkhw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtzhfgiyvy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtiqhwepyz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtlayjenmk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gthmsmtnxt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbjbumlc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtqndyxaxi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtfzqwmfkd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtijhtqujz.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtypcjsmam.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtebfurjpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtwkmllytl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gterkvqmtu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtxsexktqv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gttmxpcakp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtjiytpqgr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gttfilnlqp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtexqagcap.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtcbrfvami.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtfzyxthkp.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbshyxol.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtxzedtowr.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtrhhspczl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtsyysizft.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtgjstecbu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtwfajjjgg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtjgabynyn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtejcerkzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtojnebfzc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtgnvuvarg.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixpuspoi.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gttvthrdrc.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtttxynxeb.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjimrexhg.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtyrrwakhr.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtiqrshzvp.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtbruwzzgy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtzvqxsost.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtdybfcnen.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gthazdmxbi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtylirbesb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtghealunw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtkwpwxpey.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtezcfxmtj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtkflcybct.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtstalbsuz.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtotjgjcrf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrvmclwey.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gttqxtcswb.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtfywljiqf.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtuwhrphuq.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtoirspops.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtmfsdkpqa.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtbyloilgl.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtaslofwqi.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtdbgxgxak.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtmmwrjtnn.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gthshnnweq.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtgvvjrqgv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtarfbinhg.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtfzoraeve.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtjiacisma.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtwcaumlkd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtoxhyoyaf.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxijvzjh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtennyaazz.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtzyggwtzn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gthoxggwpv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtsynzpjlt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtjsnbmvui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gteohyfmld.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbojcylnk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtofnbisyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtxujlglxb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gtpvlzlbum.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gticlhvtif.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtoicqggwl.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gtzeflgibp.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtzogziwgq.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtfprbqdvq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtppvqjpvc.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtkxxteysg.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtfaotrvfh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtjoinpgwv.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtudtlxbis.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtlkqmrcbp.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtjwgqamok.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtedzekffx.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtsxqcwhsz.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtqkucreah.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gthfrnglxs.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtczxxptop.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gtzzcdpsfi.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtbyfeauel.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtdoafvyiq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtiscushby.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtclbpkfje.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtwustphws.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtuyzcwkru.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtdfwgwape.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtnjldxlzq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtdkjylfxa.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtuxcguiyq.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtcrbxviux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtelmtemgv.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtohgkuogx.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtglkscauv.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtfzfhtiyg.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtzemoknwr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtuoqmcugd.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gtrluncdgc.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigfzy.top/Article/details/gtvnkzmhif.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzswsfyy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtugsflhzd.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtiukelvik.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtcjxtzlsn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtujbfmqtq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtgkdmocwc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtludbaxox.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtxuhcktfl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttfjczhfq.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gttxfxcvmg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbcuidgcu.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtvxnurmfo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgknwhktj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gthsnidynp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtblwghubi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtoybrqlbg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtnvwmcvzx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtpidcifts.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhaaviyt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtvptcoczm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtyppzygch.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtymfxslon.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtvwdqlkss.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtkgkrcrih.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtjojylxmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtpdouhprm.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtelzylltr.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtrpgptxcx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gthcxpxbdz.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtxuwbksaj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtdbganxwz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtobxunfuq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtzvvyjuas.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtwshtzuzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gtxwqgibzr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtutfvgoex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtgehdnlgd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gttzljrbqx.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtlpbijvwx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtpwpgcbhx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtodfweohi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtlwvujdgx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtsenmqsnq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtorbxvehn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtkgvkloam.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtnaooydnt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtxevlgqvo.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtcnzgrurz.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gthozuvljx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtvcacpgqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtnsxipvpu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtueefuqbp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtgjdvczwc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtjfqpferh.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtfelugvrr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtilwnqaqa.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtdxbulmsc.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtyqcchhcb.html

PHP:  $s === strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkdohaaki.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtblvfiqml.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevdylwpz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtafcgzbom.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtkndurttb.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtiqlxcsdz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtsqryzrrc.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtoffxrcrl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtxuxfmoyp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlitrrrv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtbcswrvtd.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtdyipgtbv.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtcennbuhh.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtgnotpkro.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtqsxkcpwv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtsgkpdxke.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtdcejmrsk.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtpcikiyby.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtjlcgkpgi.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtplkbqsdy.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtuhnquxvq.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtsnvikrsz.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtzontnhni.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtjfpjwouu.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbuktudy.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtrxcpnjet.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtgyzznyru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtqalvnotq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtkltcvajk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gthyeaminx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtzecclesl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtnhdznvyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtasvldvjx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtatifocri.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gteytudhqr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gtmylobhec.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdegxhkd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtepcdclcf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gtnvxqheaa.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtndolpokg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gtwubgkxry.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtlzxeacqg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtkqocjqkj.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtzkuwkcff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gttxmkhnei.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtocsjssfg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtctqoeyje.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gttxolspgq.html

Java: // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gthmmohknk.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqcbjryv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gtwqaxttoc.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtgoofpwwy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gttqxrsloh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtysmvjbik.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtzpbtwvpv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtnkkubomp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmzwdjlo.html


<!-- 参考信息 -->