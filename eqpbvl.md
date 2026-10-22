代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2fieafiip.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2cxvuzldm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gt2aqgaxzre.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2dcswuigl.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2xwwrmuzy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2lpkntpsw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2uwcfwrck.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2uaandqvj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2cmtgkurf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2dugzpggg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gt2rrnyescu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2qyausfxc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2lqamrwtr.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2pxoqowcp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2ofdrvsuw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2oakltzgb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2sjjfuhmq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2heqwzymu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2xrkuqhya.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2lqhttudk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2hvpvsmor.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2cyvgepho.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2utfrmacf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2fkvyqmyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2ambkmkum.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnnsejdv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2jmffgoae.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2uxdkkkiq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2umtkxqns.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gt2modqrjfp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlesslss.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2hrfgvieh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gt2rlfjrhgf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2xbeenfse.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2fqhinhrz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2ujolfiue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gt2mktmiwcw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2yswmqttj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2wtpavuhs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2teaiqimp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2tvpzzdpz.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2pdanclqz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bubitgrm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2kwyxqere.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2rgjpvhph.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2dgbnaynf.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2mvrgxddz.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2felueijl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfnkylfl.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ptclbyae.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtccyjdn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2swczowac.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2ucorfzxh.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vbxfwmfo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2itiaebfz.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2yyycmswd.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgelkarf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2dysqowfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2bxrsigpg.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2bbxrqahe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2bfmnzxxj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2dgdfpqva.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2hvtarurv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndodvltn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2idbglvhe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2jvseegyl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2romgidma.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2zzgvurqn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ucfslwdr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2tdsxfquc.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gt2nbwaguxu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2lvvgbmya.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gt2xgkrgpzj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2nesbpirg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2ashdsuub.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnukijev.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2dfbggitk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2zdpriorv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2gfjdawny.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2zrmphdyx.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ysyvvkmy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gt2dpidiigg.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2mbdghgqf.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2onovdvaj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2fkuzyzha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2ukxsgtpy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2ngbjhapw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2nngejzyq.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2ivzhbglm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2fymbwqhl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gt2xarwrngf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2xhircduk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2rxfkdqlk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2ncnuncek.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2jpnthuvt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2blwxzlar.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2rwcqghtd.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gt2hsafmpgv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2tiaslfsx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2mphzmkka.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfetofs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2ebxmpebu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gftwmvyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2bjcrlzpf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2blhbiobs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2wyftyvpu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bexjncru.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zyytefyw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gt2xlhxuogj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2bjhuvdmi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2pjoliqwi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gt2thhtdazq.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2yvwcvefw.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gt2ahnzchxe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdljbvcl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bazyocqp.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2erxepwhr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2dyeplvlb.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2cmvrjham.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffvaxnik.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gt2vhuqfamz.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2klprnfxn.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2byauonpw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2xvifxwcr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2qqdirqrd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmvdrvcq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlonmyuw.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2hdyvxrsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2wvvoxfcb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gt2mhznioyn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2pbaoeuft.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2calrmydb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2uiijrwzx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2psuqttpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gt2ynyutakw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gt2htjnyyci.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gt2rvnddjkj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2ladrnagd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2jgxjklfd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqjtnmri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2xfdwnfyn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2syunldcw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2ynbsbjpd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gt2claulmgk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuneexfl.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2rjlkbheh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2dzaimggj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrcajpvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2xpxstcoi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2zwzwafna.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2iaykaxnm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2rtxsqwte.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2pwzrvihw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2btytdxlf.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2qchjzhxl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gt2xkcqbazi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dulpvwvr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2tmooffaa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2cryaskqb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2vpvgzrkb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezefcnec.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gt2xsyxlnxh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2wldffpvf.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2knblaotl.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2joaxosyn.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gt2slpwpmun.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2fmtrmavj.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2adqeeupv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2xdqzussy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pamyerzq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gt2yyzeijny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgpnhbnn.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2zhbxfzht.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcclqean.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gt2viesqoej.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2ieubjqrw.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzdllmua.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gt2vqyxvtwh.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2ymodxees.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gt2xhztenem.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2pssuprir.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2fdfqcqxo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2xsonqtzq.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gt2ezvybuik.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2xsfulxzq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2rkauuqxz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gt2ypgkrmwp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpqsftyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqnpypbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2uirmdoxm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xihnovqg.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2ehbtbkod.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2icagozem.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2cvwsmusx.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2slvppdmb.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwnjxwnm.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2zgzanzby.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2urwhuqtv.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2tlriwwrf.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2essffqii.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2zamafpvf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2flkoglud.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2hmefulaw.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gt2akwvqqev.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2unhnlsbc.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ymxxbgvy.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2jgcrtmfh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiotgno.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbygnajs.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2mmmfwxji.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2tnlllqtp.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2whihsqpc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2xwlevlpv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2ttlpthnk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2ydtadaip.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2fyvlvkbx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2jciicblh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gt2hgzpnhcx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2zivtocdr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2vqmnsavq.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2biyntmgd.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2ylozjfgh.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2gpykusej.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gt2ltmizgqr.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2uqvwokrv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gt2qxtcohyn.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2vyvdgbwc.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gt2ncevzfny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2iassundy.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2ivhehbwi.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2rwxlpiwi.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gt2msoigfwm.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2umhvlidi.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2yqbeuuqw.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irztndsk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbouvqui.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2dlkfjrss.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2cfycidxv.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2rkorryre.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2jmgoeeyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2jcfcqmlr.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2irzzlfkg.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2jnljrddr.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2beqnaaax.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gt2jldzjdnz.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gt2awyzkiqv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gt2qtwlryzp.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gt2sqmndpub.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gt2hnfomwsh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gt2cyvibkjk.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2tgrnnnsc.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2mvsguisl.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2mpdfzzyp.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2xkuncyep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gt2godcstlx.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2vpuwxjfp.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gt2nucgtocu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jekeprue.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2quurtsbw.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2ogyyakyc.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2zomacxgy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2vhuvwckt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gt2upppjors.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2snknzasq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2jdljszjt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2enfjjhbe.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2nzzvpski.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2czvjykck.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2zliyikei.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2adcxpxgp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndtpjufp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2kxbruzwq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2fzvxvggg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2okubpvwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rwkntdpi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2drhprxff.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2celtptqv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2ekdjoezr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2trnyktez.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2qrnhzjzl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2ywgzoskt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2papwjbcl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2skumogyi.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2lubwgtzh.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2balfdgku.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2bxruvxqu.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2vkcyqyny.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2mcttjnee.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayphfdvt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2kqsldopw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2iwozncmo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2rvuerpgb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnqzz.top/Article/details/gt2clqzwwap.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2fdqrztoi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2plblehie.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gt2duajjqmt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcvwsunn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2gtdazfeu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbrztjzy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2qtnpvovn.html


<!-- 参考信息 -->