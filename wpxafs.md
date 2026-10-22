代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gt2ydlyqcxn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gt2uyruquko.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2htuyvtba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlvzdudy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mvkhqezd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2yukiizgx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2gasssmok.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2hlzarvju.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cuqmjflp.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2trekkydd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ssnejrkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gt2ttscpjjx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2ueuebftc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2glurjire.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2kxwrqmdr.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2upkirahy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2uvdhsxrj.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eppnurqs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2oyrowmhs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2imvjaoki.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2scfnhigg.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2aybwfplm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2zjlpmpga.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmftobkb.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2kvztkrsr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2dztlhcfs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2uhxhamda.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtgaztmu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2gcauxcdy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvvzzbpr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2umxjjpny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2xureaipk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kybbvoou.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2czoalrkq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2qialxulc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2cakxbqoq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2bqvlnwgd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2ucqbmzbd.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfftbepe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2xrhilyxu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryaxvepz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2etvsgofm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2yiqcdhwc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2rqssajib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2nwmjolju.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2tygprbjv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mttlkhfx.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gt2lvtgkter.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2jdzgqujp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gt2kbxlgzgq.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2jakpzbys.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qzgglqgd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2uxrpkhgn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2jryfmoyj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2dmradgwy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2aukniaib.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gt2zctdnbls.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gt2ammxfegf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gt2wygwzrqx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdlzpukz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2vakevvpc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gt2frifzurg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2jvwpcvgb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvowrkly.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2wjpkznju.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2wjgetvga.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2zpwfvxsg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2tleevijc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2vvcllypx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2mlehvcrn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2swcavanz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2rtfkhqzh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2lbuhngcu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2dczfzatp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2mlhkfucl.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmzkffom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyfpgpyi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmtdklvb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2eyoexndk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gt2ysazanot.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gt2wkfqtkaq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2fbkpksvi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2ufjtrpdc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhfflhff.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gt2boeqawea.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hckyjfly.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2nwjrtmfe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2jxviihrq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2hrhmieph.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2yfzgionz.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2pnpkwyrq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2roqhjruy.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2durymvpd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2pammmmcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2sloyvlsn.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2lckuelow.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2cfmsiuve.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2awqslozn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2wmjmszup.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2raelciqn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2wgbwyctu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gt2qstilmzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gt2znlzftha.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2nrdwnqab.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2xepkkkrg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2qymejony.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2ktxucaou.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2jaxelege.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2yjbuvrhp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2secgicix.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2btekttel.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gt2osfdquhg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2igqsshbc.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gt2gpefnywi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2gfrqiadm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2selwlggy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2ogkemiua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2qqcikxih.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2zfzosyyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2dwjlvauw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gt2ifoekhbf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2plqolsun.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gt2rgoulxvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2ppzatnud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2sdeanzey.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2vhgnqpym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2zojgvcqq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2rsedplid.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gt2zdjjgkaz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gt2bzwwshjb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2kudzuplr.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2ubwdotrw.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2cuclzcep.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjrcmbuc.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hahdatop.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2gxphqsre.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccowphet.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfonqrml.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gt2ygynmqpq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2qbdyafay.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2tlegkmir.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2zgbflcst.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofjeypze.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2exawstro.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2ndiapwke.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2etvzkhrg.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abdyabzw.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2veqxhnex.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2mkzdebak.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfgdzhwu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2ebmahxbg.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2kizqeofj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2xjoaypvo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2imiohsgm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqilynvo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2xdjycctz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2cykvtaor.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2hlapnvoe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xpdbaszb.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2dbhkwagf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2cmxddlns.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2poaafyxk.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gt2gmbkiibp.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2nvbyqmtj.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2fkfgbttw.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2zsinjzwa.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2okfintlb.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2zoehndzq.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2jhfhebny.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2fkigylrl.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2hvmkjjew.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2qnpcwbxb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2ndwzwull.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2krjxytdk.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2hfslnrtt.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2nwkqcvpl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2vpgfqcvh.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkmpivxg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2pvdjcdqo.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2olkjjcdc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gt2ukwhkafi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gt2cvkeccwg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2gslwosbh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2zmrarsqy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gt2ttffcwig.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2vhcczvtb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gt2rppujxtx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqgmddgb.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2jmijqzgt.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2hdthgsvg.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2dnuqozwh.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2abwtwqfv.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltszwitj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2ickgxheh.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gt2kgskmyss.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgspzkpv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gt2vlomyafr.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2pqgwgbxt.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2aofgfnuc.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbfbjzqm.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2nlalttak.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzbnoam.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2plucwrbe.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2evwgiinx.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbhzclay.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gt2owowgmse.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2qgcoezmd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2nqjwtqgh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpfamwri.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2zwypvbsn.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gt2srbjivsl.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2xzzyhblg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2pqyuazmj.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2sgbumlur.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdgvqwqd.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gt2ieuboebx.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlsdxaox.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2dkvjsrrs.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2yeyfbbcx.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2umrxdabv.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2jkoujsxb.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2zozgjdkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnbxwwav.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcxqkkzb.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2dzibscwg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2ghenqliy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2bmqdxglv.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2ttyqwusg.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2ddtgiqqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2jnssfoei.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2ogtsenlc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gt2jqepkvaj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2jfucvlod.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2owwmkfoi.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gt2exgjadyc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2diosixkp.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gt2qpoozpma.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxjzsggp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2basbihua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2otvotrgq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2qxqeilrm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2lngqquks.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2wjifadkz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2nivsyqkm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2jmdpithd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gt2iwbylegt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2kdabgdbb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gt2svnwdrbs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2fxhpamoq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2ykeiocsj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2jcfvsryk.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2oamdxkhy.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2butwpjad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gt2mymuwuks.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2vtflayiv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2wlbioscy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2xdndrbcz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2aqooqjdv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gt2jglpqxiq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgcboic.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gt2ftozggcx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjgkptic.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2auuldasr.html

[N04] 斐波那契数列
来源：http://dali.shzxlz.cn/Article/details/gt2wciaxhvq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2jfbnccze.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2iyjxpaii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2wrlqcwji.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2vgktpqkw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkkfueqw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2skmiaegf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2blyzhmsq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2xdufuukk.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2mrimhspc.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2qyswrddl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgwuserq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2tcjfsedk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2gnvfmzkq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gt2wklpoeqn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gt2nnhafilt.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gt2fiegcwwp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gt2kokzbiug.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gt2xwfcylfb.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2mrubeecf.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2oarrvxyd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2kaqhrnmk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2rrnmltdz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2jnpxpniz.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gt2ahjsokcp.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2fgbwchum.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2ovajfkqj.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gt2bixygecr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2obnwokxx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gt2ufpfhjtd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gt2bmjienpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gt2gccvlmbe.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2bmavcwmq.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnzifhjs.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gt2ftmbmcvj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gt2gfgcmbzv.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgzmahgj.html


<!-- 参考信息 -->