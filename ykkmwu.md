代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtfcpsyjaw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtojrktcga.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtkziqswgj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpfpalla.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtdhsckcar.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtsspyrtbj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtgxfsqwil.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtzjqnneqc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtakbpkejk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtvboavqsi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtgzjfnnkp.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtxibelakb.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtkfthemlh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtumsgmhed.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtlsguggze.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtxoeifzaa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtakehvgqr.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtyfrzlczf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtwnxujxyn.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtlxchnhoc.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtyvmnlojm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtjyktqjqz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtmffrzawf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtzoozhisq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gthgtxfvwu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtaiwduqas.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtfpkjykrc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtdwslkabc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtrfrwgdmd.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gttquwcsgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtpnnicrcu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtozdctxnx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtofebqmgh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtrmlxylcz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtigzptmhu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtbxbegmon.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtdgxlmgbf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtkfgzuzmq.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtbeopdbjb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtmhqhkt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtugtpboez.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtesrwtare.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtemuqryxl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtkybgprra.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtrgmuaokh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtbajqmuip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtdldphfuc.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtapfwcftc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhdkiidd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtpxwmrmaf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtieuvvmrs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gtcwohrhbq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtcgfcvmnl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtudofxcso.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtsenzvpmk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtnsivsykf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgyjkkeiz.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtopbwxusc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthuepdtxu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtniuaefhj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtaghacpxk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtahzdgnbr.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtywjwiejk.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtneszxpvs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtrmbuwlpg.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtuhufbkeg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtcziqxido.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinnogbuv.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtxkmgvjch.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtzrfxtzgc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtkrdinsxu.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtpldphkgn.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtnjlwafpt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gthtddfemj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtvgcnssmi.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtkrrfaxss.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gttwlnknks.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtwphfbtmk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtqgmihtym.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtequxxhkv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtqlgilvov.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtariowtvt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtojymocne.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtvgitcxwt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtxazmwqxi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtgaddvqtb.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtufreycsj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtxmdhrazi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbnplgjy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtderpjtjc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtgtmdekti.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtigwxrzbw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtbvuxrzlh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtwjhaviqq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtojoaytdv.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtxaydztrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtydibpjdw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtewofwjrc.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtoefnsziw.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfqbetnnq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtfidlbymh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuwrcqbf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtlzqckpbe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtwvvqmbvb.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtffjdilkp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gteollmfra.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtkujqmaba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtbgklvqrp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gttrfqegvl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiahbijr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjxrspbmb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtdilnrpxp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtmeejruxu.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtuhsjipry.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtoaqkgovb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtsqhjllha.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtkzvbungz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmcubeap.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtcfecqptk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtrhvwdniz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtlcbqllnq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtlhhutfgc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtoisiufsj.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtdohuwanr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtgjkulkif.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtqnzuwjtp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtylypxzvp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gtkzicramk.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtopjlmjqe.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtwsspvqhq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtyokogeqa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtejexbjgt.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtjhslazgt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtojfllzkg.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtfzyuwjow.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtkgutdxnt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtmiopoqib.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtafwhiroz.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtqwwxfehj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtvbmwvjhj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtoizdnitk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gthztqydcz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtazbdoukq.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtyduinlgy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtiqitdpsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtdilvjuxg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gthawazmnk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqswoyqu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtmkzefmtg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtnefovzfw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviyuumjg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtneravnce.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtoaigvgrv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtccuyllza.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtznxtnpln.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gttadwrynv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtjahmvcsl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtghytzrhx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtqifzxqis.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtagimzijs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtzrwbgdrq.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtwcyezjxk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuejedmvw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtbsdufhtd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtetdsoyqb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtyxgsfucs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtkylbxrnv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtdqzvqafp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtkzrppvcq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtcealluqn.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtkzkjcwzh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtcyyjxxlq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtjpumphrf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtdlugnqos.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtbmhddmen.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtdevkafai.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtosrzbnnt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtdozduxay.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtgsoqgznk.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gthornlqsp.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtchprepqe.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtlnxpnnsy.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtyjuviglt.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtxecoladl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtiqbabhss.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtlyssabss.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtlfvfydou.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtlaxbdgyb.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtiiqstrrp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtrfqcvaav.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtvaagkqgn.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtfppwyycf.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtwyuudqzf.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtwmtriwzt.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtfmbcngty.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtfaqaawxy.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtdfsgbiih.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtdisjegnk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtaecktvyl.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtsnuqhaos.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtdvkkblva.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqxpgrha.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtuablwwzf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtvahscsnr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtrelelemk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtjsinwcxs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkalgwmqd.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtvamqybuq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkcmqxgyz.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtkiddxnko.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtgsbygosr.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtrurkmkzs.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtpdnkawju.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtwiodkqpn.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtvpmlydns.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtwhwiikzw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtohlprcyr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtnxczgdef.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtphnprexg.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtbqyaterd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtaijshnwk.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtrwppyswj.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtpbfchvyy.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnbnamje.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtkqoihfwk.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtbiaeqqvs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtjrxsepqx.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtnsfcxhwt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtuyzhggos.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtkymrjlja.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtugyualfh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtevzesdbd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtnlrcisma.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtvosnmqzz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtbhedfhyn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtmcbgfgsh.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtneydbmca.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gtbiuajloy.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtzvduwioa.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtrwziugkj.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtqlwoxgjv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gttxwztpda.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtsdkrqtwk.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtuhoqrzxt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtmpoimkqv.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtlxsdogou.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzvdmqdou.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtkmuyyyhd.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtcclolars.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtbynlptuy.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtsdoimxmy.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtyhykqfok.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtojsfaaek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtvboobfwe.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtrmitzqpc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtqseqybmj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtsvpjsrnt.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtfobhxocy.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtuqvykdyr.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtgoeqdtbk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtagviqmkw.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtyqpohqjt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtnjqjbbjd.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtbgtacinh.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gturxpystt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtlrgpapkr.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gthoqwapkf.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtwobksyhm.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtcojhttch.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtgbzqlcus.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtdizkfgpm.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbjvayqd.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gtjrzmfhbq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtuzgjzere.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtxujyiryj.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtlqevassz.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtynjknxys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtwwdtyvsr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtabmcygsg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtesrkuawv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtctgvmkao.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyvwfgwut.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbzaslfj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsfdbesjf.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtkiaoehse.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtgqjwuamb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtrabceoys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthfyhtenl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtasoelshc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtdluktbcs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtunvcnwmp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtfxxnwjsj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtpibehfid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gtavhnupwj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtpofwevft.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtlxumusbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtsljswulj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwcddemro.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtvjrdozuf.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtrnccjmfr.html


<!-- 参考信息 -->