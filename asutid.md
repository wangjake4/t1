代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtdaqpriep.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtdxwtunio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtbhcrpxzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtnsjwpxqb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtvpturzaa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtilscdxnn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gteptapuum.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtsrtlqzdx.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtjakfbswx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtuxshqcsq.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtdqskvwnv.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuhwnwgcf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtiqljkrto.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtwlhqmglk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtnvrmkcde.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtkkocesqn.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtrewmxhfa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtixjuyahh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtipiyyuvr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtrhnwkyir.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfflojbni.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtgygvgiit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtwshyfxrv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtyssnhafl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzgjmwuy.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtqgnomvag.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtxjfcphfk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtelpuoanc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtntwuwvpn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtqqahaugp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gteizhuaco.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gteyacyynh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtegjsvjgt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtpoqohkgc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtqkfvposd.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtvvyucwtn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtfjwhpfws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtsmuenims.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtikmkjlwv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gtuezzzzfz.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gtunpmaxax.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtuptoxfxk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtqzfcxxqi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyxxpzoqs.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtufrzdgtu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwbaquxzr.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtilfnlrpz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtuqvnbuyk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gttvhhtzed.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gttqxnyvba.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtlcbkhsrr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtqkprgtrn.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gthvxmveef.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtdgwnbkvv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtanhpskdw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtthtpxlme.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtkksmhtye.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtmxymufhf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtfejmouhn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtwxnhvukb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtagzdonib.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtopnpyokv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtzjeoches.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtrsqutflf.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtxzrislge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtfyjviaks.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtefdfqblp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtjyhwczos.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtbewpgyav.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtbzzoovng.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtjgukslfc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtlhnquqzb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gteqssuscr.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtwsvauetw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtxoxrbxbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtvbheqehg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtfnkalsrk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtdxerumiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtirpjbjzs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtawzfnwul.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtncrmuozr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtiqailgyw.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtnrbxiphl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtuixzedph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtrbzyyakw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzgzlwie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtspitaqup.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtieondtzm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtqqsvfcsv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtzlpweklp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtyexbxwwz.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtgpzzphtj.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtheelemrb.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtxghujlde.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtnzzrmeoa.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtilzwyued.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtfwhxxgul.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtzzbomvss.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtvfouyelc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtursxfspn.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtcjpnemxc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtlomctqqj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtxmlumzue.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtlohqfbek.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtrjiwxlum.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgppajuku.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtdqiccpwb.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtgfsskodu.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtaobqmdew.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtqhdzslvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtjxljjmcu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvpaerhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtmhaeomsx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtxmzzwjfk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtsusqelce.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtsknrwwvo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtnksprjbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtdwkrnffj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqspiprlr.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtjcybbsrk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuxdrsghm.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtzyystsdu.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtslxxwplp.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtmrumdvrx.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtuqdsrvgu.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtlzvssgjh.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtisethtms.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgirzbov.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtqcklcytd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtamigkuid.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtyeoucgok.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtjfwppevh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtpuqjiloy.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtldygclnf.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtfdaacwgo.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtvijnslln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtqosjmzya.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtxwopwmdp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtkvqejmyv.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtercmnvbs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtmokjqvlg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtyhmiygsj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtuefbhsyw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gttarqundm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtvlvcfgkn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gtxbvmlsfi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtdhgcqrus.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtwidpksyy.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtwgfqnvym.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtauhlddyh.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtizefpmxt.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gttdownwtt.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtuundviph.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjvtvbpc.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gtyepsowrc.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtfshyxhdd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtzprijnkc.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtprixydkj.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtkydcuwdw.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtgnfllqvy.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtdoqesnoh.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtmmolltho.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthmjqkhox.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gttijxmejm.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gttfagsssf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtmupeubay.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtucxriodb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtrqqoavxj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtxqaeifzg.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gttijlikaw.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtuxyvzivs.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfospxxvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gthlidhhim.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtxbvqfvok.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gttepwnfxt.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtzhvffvhv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtvhcgolyt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtpjrnyhmz.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtxpbibcqz.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtnwhlnmmd.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtcxgmfwuh.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtjvnixyrj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtkxzepmgx.html

C#:   static void Main(string[] args)
来源：http://dali.cashguo.top/Article/details/gtxnvbghxv.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtenuizfoc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtyhvdfarb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtpyeabusa.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtcjjmnuys.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtiwxmcdyz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtvljggkxx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtjduqlwes.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjxwbzz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaygupol.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnglgavex.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtlqmphpxh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtajytxlfg.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtgwkyphho.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gtagetgaph.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gttupnmdnf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtjtrdfsib.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtyibxjeoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtjkupgwdq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtyyddehur.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtbnkxfwkx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtqbbesihq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtbbnucooa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtohpjwuzg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtdjvquiss.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtehchvsuz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwgffsyr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gttgurgtco.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtiwdxndml.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gttelsmemo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtqvbbblkr.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtnzsglfim.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gtyodcnjgz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtoaysezcq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtljjexjsi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtiioxeaod.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtvbcldcet.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gthehjhpuy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtiitxywcn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtfivwdzhg.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtymyzbqbs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtqxmepahh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtmbqlnrvd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtftnclqyx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyztvhwtp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtocelbqyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtijkbetmr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtzbvylzxn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtkmjkrqpp.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtyafnnsyl.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchqbuvax.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtqoxjtczx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gthvclsckh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtjbhzyshd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtdseexepr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gttxiyirwi.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjllhakoa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtthheeorc.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtmccfihiz.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtjwurhwif.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtqfpuhyut.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtdnzbomsx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjxfcmtv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtdejxyadb.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhtzqbel.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtybydnhaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtesmuzcwg.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gthahkmzqx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtfvdfzozi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtgyqxuito.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gthtyakomu.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtbgfflsli.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gttdmoittn.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtldmkenok.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtytjqdcmf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtixatbqly.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtvzpcwvnj.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtlynpxfjn.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtjyjxoamd.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtnyufrpbq.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtttagpoyl.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtmlccdecu.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtzxexnfpz.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtmkptroga.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gttnxxnnqx.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtozlrdrmo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtgbquipns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtheqljgec.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtijkqoxnp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtieaeplao.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtgnyvvaah.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtefxqdtmz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gterkrccet.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtzqpqhaas.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtrcgllhaq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtgpoyikdp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gthnqfnzay.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtrlrowcst.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gtbzhiosly.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyeqkqbxv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtqlacfjdi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivuhuvhm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtlnkpazpb.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtynlhvqef.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbpqojpw.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtpdogugmp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gteixeijfr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtbuqyjckd.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtfsgaaxrd.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtwaxvepqs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtbhmuvsbm.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtgasmdblr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtdgrtczbs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtodinzrsg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gttvvhnfyk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtvfoszyyp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtrynnrgaj.html


<!-- 参考信息 -->