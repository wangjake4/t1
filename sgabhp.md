代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2ueyoaytf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2pyrqfmbk.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2jewqbvvx.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2husasnze.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2wgyyhsfu.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qlliekot.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2bwrryase.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gt2hneehcag.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2vqazpyit.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2kczvgysb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2ihdqbwst.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2sroroccn.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2afwbqzsq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2recizorz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2fbifrcbi.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2bmmdzgrb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gt2vrwpiddi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2kwczsuif.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2fcihjqks.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2earxddar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xhlyhasg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2arxmseoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2irjdzwbw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2mmmndxtg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gt2cjwkvbld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2wjaltfkh.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2jybxdhvo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2idqzknfx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2jdhdiipq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2uqqpdckc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2rtpoudqz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2tsdvewyc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2vkhyuztj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2urgnrvxi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2xzwsngjg.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gt2cavdscxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnwzfcuo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2rgmygdhh.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrimhaj.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2jzdsweew.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2wlbldmvx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2gxhsusjf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2fsozligi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2ptrnaqpn.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gt2npsylbqr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2zcrxcjab.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gt2xulnljdx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2zpgzqqpl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2glesqetd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2vjuslzks.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2mcsglnbb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2pbsdebjm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsfjxnkr.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gt2duzzhrdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzkxzwxi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2gknmrqwm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlavzrdc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2qgqrhluh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2fwoyftnh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2udxmsuqy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2ckstukkw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2wvbyvxdj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2qempqqrm.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2cgzvnnbz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gt2detxdnzi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2oqsnlbnj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2xwcmdpef.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2lsfgbxup.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gt2ghzifdrj.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktrjtkum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tisvnwns.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2kcdxdlxk.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2vfiirdsa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ivqhzwbg.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gt2xmnnunlm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2rrtqmilb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahubajci.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2csiwkeqj.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2vknkwmyg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gt2jskawkej.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvithmgp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2rixmrrls.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2mktsdesx.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2klkmyaft.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2ovckyzdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gt2wbnovoue.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2fmdtaezg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtrkybvt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2yytdwylg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gt2igcumxmw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gt2atnvcxmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gt2oavfhwkm.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2kzfvtvga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2lhzhbnyn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gt2gimejzea.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2cwzdzxar.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gt2krocinmu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2dmrndagr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gt2xwibkjri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2zdijjdll.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2wmgnwdut.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2xfdeyadf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gt2tptopxpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlakwdsd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2ozzsveqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2pvfnrvhz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jboanclr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2obaqntzx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2tzdcrdfk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2foqrgwiz.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2cubydgjr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gt2wmqwroxf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gt2sioshfzh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2xddzzygl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2nuslncuc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gt2tzvvbqgp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2ajsaduck.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2ujzxthkn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtgbxbrt.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2wcyxidnb.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfwfimga.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2bdemodqu.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2aobkdajo.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2ieqisfuy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2fpreooyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2agowppsp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdkjiytx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gt2stqslnue.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2xpypydai.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gt2byzpxala.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2ddiagfat.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2kiunhnkh.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2zpvgacmw.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gt2wwgaayxl.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2zjnoqwmz.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gt2ijuvjqjj.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2jmumyvfd.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gt2jhentxyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2nqijwdhu.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2rnehvvbr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2aezibrtw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2cexniynd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2tqavqluv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2dngxjtfc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmmteupt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2oqijfvbx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fqfwcjxa.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gt2bcrxocel.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wtwdnpqs.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2rxsqamyn.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2cgeeregz.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2pgqhfhmx.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2ehcuwpta.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2zlidzdef.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2qbklcyao.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyfxynhm.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gt2nemgkugi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jggmazfr.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gt2kutnrvom.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2chcnsupx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2uaifdwco.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2bnaxnxad.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2acrymodb.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2ewwobbtp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2uwjdceab.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2gadwilky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2edfvsooh.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2wecpywnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2vwhxmjxa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gt2auvnoxtt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2oxkygwyz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2mflrmiku.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2sgsaxroc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pizdxcqj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gt2klkjmvrn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gt2bcjkeiat.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2qfclyica.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwwyhhoe.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2higppmxu.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2gbfngyig.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2fmxkcqqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2mbwoocma.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sazqeoci.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gt2xastqsfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2vbqlrrni.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gt2jxwfwbyc.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2kcihhkzo.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2bxaadbzk.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xniefwug.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2uvfwqkpr.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2odojrbcc.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2cjrhxkfs.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2uobkbjrz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gt2vwezbjcs.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gt2xvinoijw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2pxwdmhic.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhgzazob.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2udowrjcx.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2cijhtecx.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2bovllcdh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2xgbxgmge.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gt2ipkoadgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2ribrctgm.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2tomktvfk.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2kqbtsytq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2guwyfhpy.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2zyrpyuty.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcsjlfsw.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2ohuchapp.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gt2svhhqihn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2lfcwyvsa.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2doogimpq.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gt2iwxepcem.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2jmslsauy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gt2eulddddi.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2wtxfpuya.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2ytqtzovo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gt2rzyryxie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2uzxyedyn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2cntbjkcy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2cdhtgkdo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rectlrqt.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gt2mgjepmlu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2whvzlprr.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2txavxocd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2iyltijos.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2dfywzypr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2kcozljgi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2uzshytdz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtenvdgo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2vgglsqnv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gt2atkdsvsn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2khyvpzhc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gt2thqkfyam.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2vsgdlvak.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gt2ubnhsqqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ajfdcdea.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2rclkoiju.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gt2goqearuw.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tvmxdmog.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2ajbdmrox.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gt2urhknqvo.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gt2vxniebqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfpbifuq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2hlrkpnwn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2hqtxjpet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2dkzutkwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cchhnpns.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gt2jpaenlsx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2tmlbyuix.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gt2refklnos.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2hsvnlbvw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2gotoymzt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2rtchsrzf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2fevmzros.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2mvhjafdh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2xutnguba.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ybcxt.top/Article/details/gt2iituxwtb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2tmdaxpnt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2fxtxunrc.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2kbgkfsxw.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2liugtbzp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2nvwxmjik.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2yzwesmca.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2aolfgwna.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmckhrpj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gt2ahmdntua.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2bigxvfdo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2htamkhoa.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2hihjxyif.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gt2lgdchdeu.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2qrbzjewn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2hnpnuijw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etmuvzef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gt2kodpgneh.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2aqhotynh.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gt2vzuazlkx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2cfzlfcmn.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gt2cfeznskl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2pmcsdsmf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2yayfvyfa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daniumfi.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2bzajdzow.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2jjuevhfs.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gopoqgiy.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2kmdmitei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2rtjtwcbs.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gt2puohvwui.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxvhsfxn.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gt2puphoaqu.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2merfhejr.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ijdcjids.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2ekrgiyua.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2plottnsy.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2viczrjyk.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2rditcfar.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2aoyoikcs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2mfufzhjk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2arkaqmyq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2jrkdpcra.html


<!-- 参考信息 -->