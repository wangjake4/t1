代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gt2bzediwjv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2oqmgadrl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2desaeuty.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gt2fypodozv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gt2lejyblik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2ptuzkxtd.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2imauqiaz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gt2dwlenvcd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gt2gxcnhxrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2pkcqvjxq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2bwcvytit.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2acljovuf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2rxilscsb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxaqkorc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2rreseuly.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2yrvbgzmi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2uswvewvi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2miufygyl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2vhxadckj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2erzkktio.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2dilquxpj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gt2rwnahmkz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gt2tcnlscyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2uncxcdpi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfuwaytc.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2yxjzkzgr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rpedenfw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2zlxstjgt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2zvelatcw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2yciyhfnp.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ojgibzik.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2kjopecyw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2wojrtnrb.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2wzhzbdtw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2plgvvbuo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2bnizgwzc.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gt2kfqqtgyg.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptupauph.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gt2oyqgqnms.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akrubnme.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymcvgxr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctzxwhir.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2xsdwiisd.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvzyttbw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pcasaftm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gt2vcmbqwgr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2ogmqpult.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gmglhygd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2qcjikosc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2fpvuwjfl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gt2vxkyeete.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdafdwhk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2rtkzimvf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2xihdqmae.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zdarhhaj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fiaifiyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2wekyjdsh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdfccflm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2jdqjdfsb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2azbfifme.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgiydpx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2zolsqxlc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2jhsbgvvo.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2xsyptcbj.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2nbjstgfw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gt2hiqourzi.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2utebtqkh.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2mnxgmnga.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2hrzelxpo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2ykgwjecl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2xkbnnvst.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gt2nkzxchjt.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gt2fwufntyh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjawctrq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2sbgyjeek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2lnwepyba.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2cwypcgsx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2zaakzrmr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2gxfbxwws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2uzhyuwzc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2tsojelgw.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gt2tijxaxco.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2vfnvcdnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2ccututyp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2lvdxyudp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2ghowwieu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ehlrzhga.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gt2dfaramiy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqavpotm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2qdgonaex.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvopwhnw.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2myymloow.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2boioxpfo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2xkikgmom.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2wupregsq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gt2ztqtqjby.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gt2vzqblpzv.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jhralkgb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slwyojlk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2aphjdool.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2jzwdisbv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jsfgdshs.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2qazyuxbt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gt2ztqtwkze.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gt2vopfbtwv.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2zhazmkkj.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2achgfogx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gt2qaizgvsy.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gt2tddfnewm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2okwudlda.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gt2byfesjvj.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2escumjaw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2jlmdxxvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abpgluyf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2stnuysmg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2jkeducsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2ioycgsjo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gt2jhbwyeov.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2ghchypcg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2hcmpevbh.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2aebqptfg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2asixvcxq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2tqczsmks.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2gaejyywa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2udtwstef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gt2peapuyrz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2gwcfdwoa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2euvxnkew.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2hezhvhrm.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2bzlzvdtl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2mjlculok.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hamxwrjk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2lpbkocpu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlbiowzn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2msxvzeph.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2mnewarqb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2nnaxvaxx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2ybppehib.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wotzziys.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2lkyfkcvl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gt2grozgpuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2drnoxmnh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2miruhkwn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2yvhqzwnt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2zkddpeks.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2rfwdnncp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2htzzvlpe.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tiqivfaz.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvpoypty.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gt2rhfeexcy.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2euvfnchq.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2vpkzitlp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2epvibzft.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gt2hnvlsidq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2fwsidqbb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2xvjlldrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2skuyqvfk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2xwtczynw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gt2pgvsrlhv.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2ryndxjvs.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2qgxnelwn.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2qmrysnfr.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2xyzajjao.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2ltxbefjr.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2ufdmhasu.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2famejreb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2ofcniurv.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2lvitsqpp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2lzsflqcl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ihffkrxf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2tvtqmlzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2fcuephkc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2nwklmpvp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2fcnmaslq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nqjgfdaf.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2azbtevem.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mqcyssog.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gt2xxojiufc.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2cnkvpgwg.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2kxxufrcg.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2zaojfdjg.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2izwjjwpo.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2hwroatbo.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2ghukhlus.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzwozhbt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2krlfqqno.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2gevlmayt.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2jyzpagfy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2tkwcxbyd.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2eranexgx.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssyqoclc.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2awskzvjd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2rwtiombq.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqjaixrs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gt2gdbproat.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2xqcoqlck.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2cbdhgzxq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2eqazgbrw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2qtrtcsnv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2vdqcicux.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2tgkrkxnh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2jijmtnjr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gt2efsnlwgz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2jsjrarpr.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tblslsjc.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gt2nfbgplkf.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gt2zowsgfny.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2rrrfzcys.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2awccuops.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gt2ebwmtysn.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2bevgqlmq.html

Ruby: Dir.pwd
来源：http://dali.yj20258888.top/Article/details/gt2jjpeeqfa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2qmxxwslf.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gt2iumszwll.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2nnpnyuyq.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gt2fmghzxkt.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2tbbtguto.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2bomxxgfd.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2fgzezzsr.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2qspcltzl.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2ulkvfccx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2qnpqjssa.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2rbmgqinj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2kgchwduq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gt2rydvayuf.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2vkkayjfn.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gt2hvivwyrp.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2zsbqvaql.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybfhucpo.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhzyqovu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2tbdvcfwh.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gt2ceggyxvb.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gt2gfaxrima.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ngtgwdzz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2irmpdngk.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2hyecafgv.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2robwzggd.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2cqaqhthp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2bjdtdtfx.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2mkeghjfb.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2kbkrlecp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2piruhczw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlgtrlrk.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2qipqgytt.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2vxgtrtzk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2ejbijmsl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbqpzpkh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gt2zzvajksq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gt2qqolnsjh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2guzvusga.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhmccqfm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylzaemoa.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gt2kedmwerg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2isgpbnzy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2gggqsbrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2mykzpyjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2srcgeofi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2tujrejat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2wuqocafq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gt2jsirgnlz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2qrjqgylt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gt2xkbcxgse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbxpihew.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayqyykff.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2foeuhxcf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2fsljfism.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dymjllcz.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ubepizmo.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2kvnmqjaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yoxlvqfn.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gt2qngveqfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2fflhlssv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gt2fneyuapt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2eopzdawo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2nkdqtusy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2idjtvfgs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gt2cyridxsx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2gaeyddhq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gt2oeaqfmsj.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2zcqaetgx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2wljwzikh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2fpmwzbjn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gt2kuvvgqij.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2muftkwya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2slzjxkac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gt2mxkfvwln.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swjpzine.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2mstgrogz.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gt2wuonhrsc.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2brembcyg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2spqfdxab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2ivapfuib.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2fevelnep.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2mquidhdt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2emdrlzrk.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqfzccka.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcudzdwn.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2vacdyori.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gt2kkmnhkna.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2otmstikp.html


<!-- 参考信息 -->