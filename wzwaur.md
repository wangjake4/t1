代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2jtgnhbqo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2srqmjzmz.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2rokpgvaw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2krcprqxo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gt2kqwdpown.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2spxaxoet.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2eoowvmdh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2prejhrny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2cxkrnzkr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2bazdfrdk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gt2qbeikwma.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2xmiiixke.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krlqhvqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2tnbvtaga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lijtopud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2czmvxwvz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2llsbfggo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2nyffadgh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2apruehjf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2ceqnqjpn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2nzvdvsxi.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2ydcjrxhx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tqeqnpqx.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2bubqtuwi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2xojzjejh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2vbhrrfmf.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2nzznxilw.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ybblyora.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkcaoxwu.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xraypwpg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2zpbruszj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2dvvewimc.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2czalqphl.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2iyahruqi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2itwbgadc.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2jfxshltb.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vevhcygc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gt2qbhfolox.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2ijoznrtt.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2wztmkodr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gt2pgilanya.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gt2hnyhqwga.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2asurlqvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2vexbpwiu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2xfcfrpvg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2rputasui.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2gajnvjzq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2kaqrrpbs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2wjcfpuoc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2yknjetap.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gt2cxnqdkye.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2xmiccarf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2fzxxkkxg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2uervbzbs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2tmcnfptu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2ksdqwucz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2dsekdnaw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2vcrlxltn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2anyegcaa.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gt2dbqxsjbh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2cpztsavi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2upgcehct.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2yhayfhfe.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlhhbdta.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gt2vogbmmyt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gt2dmjketec.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgwlxuly.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2nditklsm.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2ijlbmzao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2ielulpve.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrytcajr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2sntcsfwa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfjpboan.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2vgetzmvy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2brjjvitj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2raoesddh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2bgoftlxe.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2rkilnbvi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2bgmqmgrq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2rwctcxmw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2mypijckq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2evnncvru.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2fkftiquf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2ooagxzkm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2unmshvdt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2fjwmknqw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvvudspn.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gt2czrolfyv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2mdijhhfe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2njkixhqp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2znhzurvg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2smfyjotm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpzkafz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2sufbdekc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2jczpfnid.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2rmqxubbu.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gt2drylsbie.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2iiadqosz.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpuevsbe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2tpmyhiov.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2kpznaqgw.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfpqraxb.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2vphgbczv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugbztjex.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2fcfdptsx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gt2innrkotw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqtdxsqa.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2ddhmhgrw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghaatyho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2fwdmpkvg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2rgttgyas.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2bcauuyoq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2uzswinas.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2trljtrty.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2pozliyeb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gt2cajoqphz.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gt2xtfyszzc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gt2gkhzetoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gt2ifycayaf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2phnuqlmu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2llgixzki.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxxvjaez.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2zhoznaha.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2zenxbice.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gt2hfltbtbm.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2lrqtfdud.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2duneller.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2xdticqjn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2ukbocbqm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2nnybmsiy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2solktkff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gt2dtzozlrh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gt2iqhfykod.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2belnxtcy.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2qmxyrosa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljkozynr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqhugsvy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2qvbjoskm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2hpfvitdl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gt2nvggdghk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ewikqpre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gt2skgkysve.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhljvqek.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2kydtuktf.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyjgkoku.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2stzhwhgr.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2pwypgtyd.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2xpdnxqqq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2zxektrkb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2adknvqpw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2zhttxqbi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gt2qtugsczo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2adhhexhc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2xpxocvaf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gt2hxjulkvl.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2qwiaante.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2cqfwngpm.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2qlcctouh.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2vsdjitxk.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfiiigfv.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2dxbdypbs.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gt2ivjkvyig.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezclkkrj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gt2fiwapzjv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2wkcthfhv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2nijahzxu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2ootmtcfn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2mpsvgrrf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2bprrtsjm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2ucuffmxf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2miyjsrfs.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2ujpgbujc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2svtnwehv.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2dgknwdbf.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2srfixyfv.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gt2idnhlemt.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2fttkwhcy.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2pidtcywq.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2nxpkjwbj.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gt2piklplvx.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gt2bpxacokd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2xytwherl.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2wnabnuht.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2osutmlub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2dsgxxoue.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2syfcmmjo.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gt2ccztflya.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gt2zieauoum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2ispewedw.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2irauxfaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muwoqfri.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2jgutjren.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2stpgieov.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gt2govoekwd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2lqhemcmi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdsvcmzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucqesnle.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gt2iyzgvhox.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2vrnhejum.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsuqcxgn.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gt2djsgsxqk.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eesduojt.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2zbreoivs.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2gczxmjhc.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2ruughhur.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gt2dtdndhol.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2ocnixfgd.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gt2dnhsaott.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2bunalxav.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2mjekhpkn.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2nnrqkngb.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2heatjupt.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2ejxgcmhq.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2zdectzqr.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnhdslsv.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rghktdhg.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2bksrabhy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gt2fhfuexbw.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssjoidwu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2tlkofjvk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2syizwhlk.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2ujqbains.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2oktkmhfg.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2uyapcbsw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2uybiqupl.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghtlnafe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gt2rimbixyy.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2fszpmlyk.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2rmtwsuot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2pqpifsxq.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2kzbtzmmk.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2bgqwfips.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2ihqezodb.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2dijrccpn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2qbmfwvvk.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2zhqhubqd.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2twumjutf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2kosnhnaw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gt2ttmbkkop.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2nreamrax.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2jzqxhzxs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gt2cusqayqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gt2nvzrhhod.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gt2xrfsstmy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2hbcklahx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wgsnliqy.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gt2mtnohlnd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qijukoaa.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihyvpqfi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2nlpcadth.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2vgpqbrqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2wihjcqjm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gt2dzalycln.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2owrvbngx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2ktylnvss.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2vytnlcec.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2ylaycmzl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gt2skckrhmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2ogeoxxxm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2gjuxrann.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2nmegmqis.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yljvjfhv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2graiuzra.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ngvinvfd.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2pegydrsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgyznwzb.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gt2pygdnxhn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2atimzrxm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2wujrpyge.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2vlsdoobd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2vasrgzeb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2qryvpadg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2wnwudvoi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2dzkiuzbp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2ktxbtzjv.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grpolfrd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2bcvagdzk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2hafmvbzi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2ykgiejps.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2dkywydcs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2ebpnddhx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fthqgemw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2eypcmyhf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2tgsppwtt.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2bqgmfryq.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2yikxpnhz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2fgsnyulq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gt2aylapscy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdbouzav.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2qfooywlw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2uqudqexr.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2moecbgpz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gt2effbayzh.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irrynqnj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2aaijhohn.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gt2vkancaoq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2kvcaqdpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2qggrxlom.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gt2nutilnxw.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2olzkacaq.html


<!-- 参考信息 -->