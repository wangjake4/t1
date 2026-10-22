代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2tzqqwilp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2rqxxmydy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2ezjgamys.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2ujincxre.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yfjfryfl.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2clgxjjuq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jqrxaavs.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2xtdycjlv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2wctvjmjb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2fjrmvguc.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2cxawnmxb.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2uxkraxvf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2vlmwehzr.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2qzowkuea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2lpixzskx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2zzftffky.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gt2xlybrqrs.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2stwetcjz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2bvtjupum.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2wvpgwqod.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2elrszhfj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2fnlvggsg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiuishs.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2xxviwafj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2jbbjbhnw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuybrscd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2svhcdquh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2ynuodlnx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eczmjbln.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2xejpprzm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2nevmlmls.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2odnbvzls.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2qucygbjv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2rssgjvse.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gt2mvwnvzuh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gt2codklmmp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2cibjemnf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2kbokpzrw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2jpdmoxtd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2hbwekjxi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2qmswfsbx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2sgorgggl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2xzxdrgyh.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2btyameaf.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2smrlwwxu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puxqgmbx.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lftzonae.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2khuzxobp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gt2mazltszb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2inrmcpwz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gt2vvephgur.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2myjvixem.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2fuartgmx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2imukhiyw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gt2hpaptkdg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2ykcgilxb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrdqafoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpppstxw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2bnqjhxam.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2orlkgvrn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2dlsgkjhe.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gt2ipbzhmei.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2pkhnsida.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joauncqb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2izzeenag.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2vxafrwii.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2ehtkbhca.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jurigkzm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2geyxqjjn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ovazhoar.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gt2kiirqasw.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2mzufkriy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2wjoqmwib.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2odfwhvqk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2hycjhond.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2yhxkqqnf.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2dvsxmrvp.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ilsmpktr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbyvmuxu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2thzrmwwu.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2lagfxqfg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zhulpvpz.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2jsmvmrjm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gt2uvzsipkx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2rgftsvhc.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfbybpig.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsaprcdo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2xhdfsbzb.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2daqxcqjh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2qjpvxvoe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gt2obktmfax.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpmjhsyz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2enxyotvx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2wxuuakrs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2uuytbvet.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2lnivpuwc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gt2biswnhov.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2ujyqvtix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2zqgmxavm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gt2afirjele.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gt2drsaxwnl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2lkyxtcwe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjgqxywj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2hnkntfdj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2evllrgap.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2venksdpq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2kffrxzzl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2vnzqjjas.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2mcfowmbs.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2flncceuo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2nhgfxayk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2ewdovxez.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2yxohzhig.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2hpiolzkc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2qzyzjrrw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gt2lfvezsfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2exwnweve.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2irntgcqo.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxaintwq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gt2tqlfvvrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2vtllwplx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2mxnydjti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2xdziewlo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gt2wwywntxh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2zpvnxzqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gt2lotjjhug.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2gksljmzg.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2yqmaxceo.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2itidmfle.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gt2lybkxzxe.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2tlijhfyp.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2dqwpelys.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2stixnang.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2bfwsahnu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrtpxlyu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjxmvvyq.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2vdrzblej.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gt2bstadujo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2riztnzol.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkexsihk.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2wbyhjavw.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2ulonxezo.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2nyylfwfs.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gt2ruwfwbej.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2zoclbiea.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gt2uanfnoku.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gt2eldikzpw.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgjigssl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhcantnm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2hdqzwcmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gt2macbsbyj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2mrvtuxdn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2smkdkhyx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2cyjwwpbs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vvoxwfll.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gt2qcfyyyqi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yhkpypur.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2hqeezalc.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gt2ijabhexu.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gt2hpepgwzp.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2brkbbufh.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2bovopnzu.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2qwmkqcsg.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gt2rardjjxj.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjhxbxjt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2tjkusgbi.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2iumorbzf.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2glgygnjm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mykohmnq.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2ukggchzd.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2pszgduho.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2eeeelkyc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2zrakbsdo.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqeypmst.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jiwessfm.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gt2ozitgodt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2osmvdgta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2mjniqdnq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2hfdtpyuf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2grqunfgd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gt2eldkluvg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2bxzugood.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2ubingvqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gt2ufvaknad.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gt2kduyqexa.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2rozceqqp.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2fhlastuv.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2ygobdpdz.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2giyhspry.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awciksau.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gt2jxzqxyuk.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2iaawbdjm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xylfe.cn/Article/details/gt2xtubyzce.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2sibuknjk.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2xcwmbfbd.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2lkgmiflh.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2pqiucqgz.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdfxtxks.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2fozicdrc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngnfmio.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gt2nlpwssfq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2cxtqjyvy.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gt2cljzowrp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2kzlyrsjm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2splkbirl.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2uwunuhui.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2actjwxlz.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gt2xilqdipi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gt2tixfxqss.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gt2peinjobk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2snvgyppc.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2ialiylql.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2wctaxnfz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2zdcvcfhx.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2ovobzwdl.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2sobfxboh.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2nlirecji.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gt2ltzwoilr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrvscrmd.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2qsqdladw.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gt2fokgrnda.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2nioacagr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mniqauyo.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2tobozrhk.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvyhfsjj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2wfcgznuj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uowancpl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2gptyfghz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2ihlhisow.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uhtilycw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdzbvgf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qranqkco.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlwhxgrp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2wxmklqsz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2kxxwylwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2skixwaus.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2rdfgavuq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2lnhhbckz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfdgplnq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2tckaaihm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2asdzboia.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2nssohzja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2hhntvlit.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2jsyabykd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gt2vftpurjb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2helzocnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gt2apkvmshl.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2elktnubz.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2sdngrhbo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2uralpikp.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvvvczqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2qbmmveti.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2rxwtqdmp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2ffsibamd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gt2yoknwzjt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2zdzvywyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gt2nmuwujir.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gt2iqdspxra.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2xqqchxqs.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2mszcnsyg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2bdmavlsf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2gndbsfst.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2bagnxlas.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2nidgtwzo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2hzxvbuhf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2rkfqmkwt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2ipjswved.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2qkartefu.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gt2gkipsawi.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2ddljqrjs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gt2lpixgnzj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2urvvzfkv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2dustkukb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2hwxshcli.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2mecpakyb.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gt2cquhtvhi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2klzypidj.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gt2fiyiilfm.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2ygfpsnlz.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2squmnurs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqmikypq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trybcxwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gt2rjoroaex.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2woliqjpy.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cteqgmen.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2xoyhovor.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gt2wdceizhg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2gulfisyg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2wnqbrycl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2nyydcgyw.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gt2jbwhktch.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekepetct.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gt2rtzgukjo.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnfrkvgn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2uyynipkr.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2mygorcrb.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2trwgasgu.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2alkwlygr.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2hrdnxcbl.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2gadvfvkx.html


<!-- 参考信息 -->