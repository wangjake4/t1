代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gt2jgoxtqhc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2vtnkkpza.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2xxsiexvf.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2raqgmvap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2jvgthvwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2ptbdasea.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anikgsbm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2uxmphebz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2naylyrne.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2xofpfhgo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2lzuaczhc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2miktpiqr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cunytgib.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewsecsqn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2omdeufky.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2wtuwjpjk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2zpsklgoy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzkzokgq.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2rftxhaqk.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2qmztwdjw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2eqisfzll.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2gazzrixk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2mzwojvrb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2qoqgltbn.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmfyzdzc.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2odagyjjf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2orlxpzgo.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2nbzusrkk.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2mendybbl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2lfxtxpuo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2egprorho.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2zhbayuur.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2twhmdxpn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2oypfrgvy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2hikmqxay.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufsopibf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2xqteeyqk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2hfbknoan.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhulbyin.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2lbqbqhyo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2qphrbcne.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2ivnizrhf.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gt2sjrbydji.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2huowdqpv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gt2wroevooz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrssnjfm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2nicdhydo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2strhzmiy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2icxnogrv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2hkoiedlt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2pesbswtc.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2jnuokcon.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2tyqaevyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gt2sladbueo.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2lhjjitnm.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2bwwwlqgj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2ygtzzykl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgkhyoma.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2fztqrbwq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2brjzxrsu.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2lwxfnebi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2qyetjndp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2qylsqdpq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2jpitqyqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2fnuizejd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2vfuyhogi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2lyxqetwm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2bufpvkkt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2nevhmggb.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2lapgetco.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2pkzzlltr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gt2dkboglor.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2afjmhwzr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2zkingyxv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2zdskxdii.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2exawoqbp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gt2jdzohgpa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njmkehqa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gt2nuhtppcp.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ahnzlnvj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2wddhohyj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2bkzcvydy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2qaxelfvv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2hrjvknmq.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2rxclvhex.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2tkcdlsed.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2fnqlzdkm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lytwcbze.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2jlommfiz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gujcrnxg.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gt2riuoagjv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2eunpklpc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2maliftql.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zknbuyhs.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulynswhw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gt2dchdxxoi.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2plfrrioa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baaksjyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gt2fqrltnkv.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2lglzivpk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2sqasauww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2gnyqfdqm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2qyzkiryo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2xxgztstz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2ymzaldxi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2cxobyort.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gt2wrhgnrjc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2fiapepsx.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2uzxtxzcm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2mhwhdqza.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2oeinkquz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2febihaol.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2soupnfgz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2ahqmjafi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2xyuwoypr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2rjuwdvjq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2bezgedie.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gt2dnegxlyb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2mrwfargg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2tfyqqhzz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2rwspwfnt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gt2xawmhzbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2aqgnkvfd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2nihcqdxn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2zycifpao.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2yltumcan.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2dvalgiex.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gt2qaqpjgus.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2pepbmlyc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2bhztlhln.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2ouxwghiq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2rufzuool.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtmzadqd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2ncxcvppp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngrmjlio.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2cowahysz.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2grvvootl.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2xpsuuyur.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqkempom.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kefyfcuw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2dgfqebeg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2kldgihnw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gt2gfpazplo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrcbvxaz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2rejwweeo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gt2wnvziruc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2mrbotebp.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2zygtrtlr.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2nsewggfg.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2tjbtmpal.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2dzalnqop.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2xvyserew.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2xuashesy.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gt2winefndw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2knjyqrpr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2iavbtdkj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwfcqutp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2yccswexg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gt2ymbkypog.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2ppwqmdkv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2hpdmzddl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2ocjghsnt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kzboseac.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gt2bgcbdqdu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xlruawop.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gt2tdvannmh.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2oxfsgcuk.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2nulhkdpw.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2zijjioet.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfgudmyr.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2dyukwykr.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2tcruziwo.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2fwqpppns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2peccqolv.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2auxewrgl.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2eodrfxjn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzywhmkc.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2jnnvzlxy.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ctzmaylo.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2ccedvzig.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2nxfcmbqp.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2zmwllxbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2jxficvkc.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gt2kqnrbxei.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2myqzzclr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2ldfcdetl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsqztpfo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2rbdhbgrb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2sdwexeqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2dogbypyn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gt2tjurnamz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2hzkthnpe.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gt2mxyttopp.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2hyvavbgs.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gt2ctdnrsmc.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2fiftzjjo.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2cgbzobqd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gt2tiuhauwk.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2qpyboray.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2cdtozpev.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2cgasyehg.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2oevljfbn.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2uxhvpygd.html

PHP:  exit(1);
来源：http://dali.sufxvd.cn/Article/details/gt2nfmnlrma.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2rcuqjdlf.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2pyrqyfqd.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2fkgkiazq.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2nispcexu.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akqjtxqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gt2kumvirpo.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gt2dvtgwohu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2tgihfzqx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gt2icvcilxj.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2zehpfkrl.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2depmtadb.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gt2rtfikriz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gt2htmzkrnv.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2eivdmwsq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2xoefvkrh.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2apfagwie.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2wagvxrnc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2dgcvurlx.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2twulfbps.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2iecmeiyh.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2xtykuqgc.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2ictpikkq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2usrgngcl.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2lvaludpy.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gt2iddwackc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2zsdfbstq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2lpnrpcex.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2pqwhnwvb.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2wzezqwso.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2wsbchmbo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2sklvlzxr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2sjtouezs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2egycfzof.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ddanwynx.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2achfvxvj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pvdrkkzk.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2brlytxxy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2ucplwkjb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2ljszvuds.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2vosvlgwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2zcfywkuh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2mqnhgyfh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2cnkdomoq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gt2ewklxyog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2thcolyam.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2xedqgavw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2gbohqzzi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gt2sfvvsnup.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2mteufxiv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2fbweaglp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gt2hrumlryd.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2czgvtdan.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2iujsdywo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfikzpbt.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gt2hzhhugfz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gt2meufwnpn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2wdehaipe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2yjwqznfe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2ljhvnxyl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2pxkjjqky.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2wxjrpbcm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gt2hfzlzyaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gt2houivmds.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2veamrtmf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2frtpfmyc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2imlljujq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2isbqrlcm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2lwaszuiu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2hzmnxoao.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkmdocst.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgdbawrd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2ojepfvvm.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gt2bvdnsxxi.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2hzhuitnp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2ztbipnvw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2qxjtacqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhvvfbk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gt2pwvtpxdo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gt2gnaufuow.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2deeojcsh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gt2qjlpkwhr.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2qhfqeird.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2mpffvlzy.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2tojdzcjl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2ojhswgev.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qysvfvmk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2onatnarl.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gt2toqelrqs.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2vqjgcajj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2zkmtfvzz.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2rbsanmov.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gt2qrskdxeg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2sddisyqh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2wvmdkqix.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gt2vgrfclvc.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2bfzhhqho.html


<!-- 参考信息 -->