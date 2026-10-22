代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2tzrgmltf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2xfefgjao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxvdalch.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2koetzvoy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsfkusno.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2colankgs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fpcpbgiu.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2nveivkxp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2oksgtjdk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2cayavgqw.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2fsywrkzi.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2noqwxfhl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2dsrlrzpb.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2uvdplapw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2oldgnzeb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2rasjaspy.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2yxoiytcc.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dtjljuka.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gt2cfseatse.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocugnpzt.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jhvmbcga.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2smrqbaxi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2utkksvup.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2htgjkqup.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2mqggkpeo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2sycjkfjt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2dcyawbyt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zosgldrs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbiamnsu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2rjfrumlx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2gxxzjhfn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gt2dtdfrmjv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2iggkhlru.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2eixzfkad.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gt2skxevgal.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2zytvubxg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2dwutrdqc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2gignuwmk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lumlcsxc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2fbslzhdc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2civfaysh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2nasmbmrr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2mrdfopjb.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2lfdolidq.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2goeryhms.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2eqhdckyd.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2bczdntxh.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2daiknwwo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2alshtxub.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2rjxnwgxm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2vlposczz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tujcosml.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2sohrkubl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aiclowxx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2azrpygth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2xvelkuex.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2cgqsfnvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2emkyjxon.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2rwysjqwc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2mqoxsoxy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2nmucoxjq.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2llanvqdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2fnbliwav.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gt2apukslci.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2ltcxnoor.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2rbdcxhnk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2hgmxtzsf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2hpjhdynx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2erfaxwqe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuousxi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2eqcmjhjr.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2rrczwowy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2gcuvwbwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2ohaptidx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2rvztqpdw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2nluzowwu.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2lxdlqeog.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2jqedzbya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkljkbfh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2guejiwlh.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gt2mehkvsrg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2zbhyzdup.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gt2vujizuvh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2oakcfofv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2ksjinhjf.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2wfonjjpa.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2rviuretw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhasnxwy.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2egfbsoty.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gt2cwfsgepe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gt2dcrbsrki.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2ihwzlkxp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebedfjtt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gt2zptprrzb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2wclfjmrt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2ltqumijr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2mwiyraoj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2ysrmtvqy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2tiauzmwd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrwwhkl.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2bzkmawvj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gt2smyisbnu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miwxlrpd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibgybwoz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2aeuoryhj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gt2sscupxlw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2iirvnifk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2hvqncijw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2umksdoes.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2kgyxpwbw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyuahzxm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2cnebteyf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2snakayfh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2xjotvrjn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2wykudblb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcxgbafs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2yhqeeiml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2uenusxgu.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2ajlqwqvt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2awjcqarb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gt2gfvaqomr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2asqytycm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2mbgzyefo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2pvszptdn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gt2lhamcuuu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gt2novzubtm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2mfuqizqs.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2xtjqudws.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2fxilmjys.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gt2oyjedgwf.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2gbippbyw.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2munuvokd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2gcrizffc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2mircfbje.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gt2mxoowmac.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2yqupxquu.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2fqdkkdtr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2zjlhtvmx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2nukxhtlz.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swyzqypm.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2qnzqdreb.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2mivctggs.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2ujppizkb.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2qzbmqoqb.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2ptzrakpe.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gt2tpymzllv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gt2ooxmflog.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywwmlvys.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2whgydekz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2kodbadvs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2jhkrhmao.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrqqumyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gt2isszjjvl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2cjpuyiym.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vuyvfqdd.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2asneqobf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2oiyhglsq.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gt2kezkbbie.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ngyzxhtk.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gt2scablzdk.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2ysevvqud.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2pvfetleq.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2qgohkdvk.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2aftqsxav.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gt2uosmrhqm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2bollmvsh.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzgxsvdu.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2azsoxckx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2oyojnbmr.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2uhsuwodp.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyemyxdg.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2waejdxkr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2buleafze.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gt2uzaexpha.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhxdqsof.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gt2yayrrbin.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gt2mvdajmrv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2rjkvjgwf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2xxvsfboo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2cwxrgzjl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2qupeormg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gt2uovmjstp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2ftbxfeoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2fcgczucu.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gt2vjbrqadu.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2albpcsxk.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gt2grnvudaf.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ihwsjcsy.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2hqznasaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2kdivpkpz.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2jkuekqkf.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2kmaatxgo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gt2nuuacftm.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuiaafrf.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2pjrbyasm.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gt2ttqfugtk.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2svngsleo.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2jsxxdvdi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgwrpfd.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2unmemhub.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2feschtog.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2uguoqqth.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2wmlixign.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xectcfmu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2qvcelmac.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2hnommyas.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2qrjgiicw.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2temyuqzu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2kgdvxvbh.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2pougqozd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2yzmtknta.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gt2lydllauo.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjbbuvmc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2zlthuoiq.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2dvslkgfk.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbwvzvlv.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2pjnbzdqx.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2jpenhbhy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2effawgpe.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfqaqzau.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2tszfqqoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzqxktos.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xiaqzpxn.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2kntryhnb.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2nhnmsocs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2fhqemqcq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2wxrtcntt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2qjomdcym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gt2jvjupmjs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fktjxuct.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gt2iexpomlk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ndvpbhmh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmplpjdp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwtovjzt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2reelxyju.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2ogeigdka.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2ijzdgmkr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2omsuqpeo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2wuwwbsge.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2uvkgugxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2wiayewtq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gt2nvyjnnxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2tsmzxsbo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rprwuhyz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dntuwcfv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2wtmwqpnz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2irnqnmvt.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2abxguhet.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2vxbgxgjk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gt2ftjskrhw.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2bcjrxdhd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gt2gwhvvhnr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2yojkrgbi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2jxyyizbm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2wzmsnvme.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2yknkvmso.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2pjoxiowt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gt2qzbbwfxo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2akxbonqh.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2ptlxvzmz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2vjhidteo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2blvstbiy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcctskao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2kmwnfmhs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2mklmmiiq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gt2miqnvrys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnojwnsv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2uumdjaul.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2mxalxmlv.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2sjpbnrud.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2dnpefodh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2eciciczv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgzqdqdw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2sdoujbrr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gt2xutkamzx.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2apzlqmde.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gt2itoisjrx.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2sufkbbbw.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2rgruhjsc.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2xheysxek.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2easiqwvk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2muzrtnxz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gt2jtrbjtaz.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gt2ndrztxur.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gt2texhlzwb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmhzbjd.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gt2zovozgxs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gt2rrepxvbo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sszlctrt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gt2cpstbamw.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2adklrvoh.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2tfkereuw.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2jdirqikl.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gt2tmhnpvil.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2iacnmpyl.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjgyifve.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2haprghfk.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2mkhmynos.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2knbaifbg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hponqxnx.html


<!-- 参考信息 -->