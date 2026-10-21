代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtlevuhvrd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtbjvfuiqy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtrjqsohrw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gthauoajqs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtlqsrbwow.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtcmjsiwat.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtfomvcurz.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtbzoxvfjb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gtucyuqrsm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtafijbctx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtjlijndcv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkiqqmxu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtqmfaiaye.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtpxiavzpi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtudrszzsj.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtjpcinkso.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgvbxdpr.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtcrslpnmc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtnjcoavyg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtatsfxgdw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtkzteekqb.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjajobpy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtkxrfrnhf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtohhetkmn.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtpyxgqlvv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtcmswoaqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtthwfghqn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtyurbckfk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjuawhtk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gteomdagcs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtdricdbqq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtjioiiaan.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gthdtokohh.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtqecirtck.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtdcnlbuaw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtvbbpbmvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtgwluldkf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtjlfhgqes.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtinevckzz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gthgciufxp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtbtyjbmza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtxlwbxklj.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtufhaeglr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtyqgipdzs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtmxijfmsk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtramwmhmt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtcguxyxry.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtvlqevaod.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtywgnvgso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gtukruzyat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtjoijnqpw.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtmidnhbiy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtpnplqflb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsfegemk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtahzibedx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtqvcygejd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtpzhulnrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtjmwprtqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtquldljnn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtmrfpkbdi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxmnqljwk.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtmhxayrng.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsplikzke.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtjwaizfif.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtzidapnxq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtxfkvoqat.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthevjqvqu.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdkzenoel.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtnntbfexm.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gtlgurdqqk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtovtiznkm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtbdjwsvth.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtinayljqj.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtodrtfjig.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtzsdguupv.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtqyowegqv.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtuofpyabq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtnnuxyipr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtloeubeql.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gthdjuwmlx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtfjtnrchg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtvrqyhvql.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtblfxldra.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtyfbwsjcw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtpxquaxfa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtignfkpqa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtlooigcph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtxhggdzfb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbjxbvrq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtusgotnzo.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgblwccyj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtykojqkhw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtesvqhliq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtslqsrzdh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtritfrrbu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtbsbnqhac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtlficqfjk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtjsrkwrtu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtrtoentpa.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtaiocbszj.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtdenikhep.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtbplvatfg.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfvmoulti.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtskrprpdi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtuiczdvxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxncbqhjs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gtvpdbmvpa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtelebihzw.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtlbxrposd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtkspuofdb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gttvuxblop.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtdvuttyhk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gttucuztqc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtpmbcckvj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtbvhkfkyi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtlswmwgqq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtefdttjev.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtoecovxng.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvltetuv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtkkrasxvn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzohwjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtmpvkuday.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtfjzwgarj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtfyjkhnvn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtkqfwnmra.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtggozhvew.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtagjdkhta.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtaghlogrq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntcbqgtt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtfjhzgujc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtabktdymq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtzsizxpvg.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtrmgbyicf.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtsskzqbsu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtpunbdcpv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfbkogysc.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gtpceduscs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyatgbeir.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtsfivoqsq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtjeeakooc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtjiyjioqa.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtlsexvope.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtpfgakcks.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtsxgicclv.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmpexywj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gthwwecnem.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtjdxqmphp.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtfznupeis.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gthnsrnoud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtelekuktw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gttvbgaevn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnztylhul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtzzdodvyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtwkavmaku.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtcvxlrczr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtktybqoix.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtfoccshsi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtmahtyvow.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtcrkocpqv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtpradokjh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtlmjlkjvv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtemfshpxy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtbmxmshbm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtpmhpjfxz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtcdcdrizn.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlinddiik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gttqpebsio.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtyrcnwkol.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtkrvvcmkm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtjagreigq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtxmzkvpdn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtmekcnjql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjcxogrk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtdculcblj.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtuxfrdlbo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtbtdwrcqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmfhvkmc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtwsnsxjpv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtqitydujm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtjihebpzl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtbjdhgsdp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtxnhurmgc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtaxawxsmm.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtqwoxjaek.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtnlydvlqq.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtquitpbfa.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtfqdoctdw.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjabnfuy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtpvdspyrf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtkjrwphcw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gteezemkqh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gthxbhaqkb.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtayeqckhf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtwlfcoaxc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtybuwkiit.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtbgtausmw.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtmonxhqlg.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtfjkputkg.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtzptgvkbs.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gthccjnlse.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtckgokupl.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtjoxcubkh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtvvlxnhek.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtkouczeal.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtwvlltdew.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtxhsczaoy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtgdcktaps.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtixiynhmy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtsalfaamr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkdrjipe.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttolicyxw.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtobeqsqff.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqnmrfkhj.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtvxibpomv.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtosioxbou.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtulpwqoie.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkijhxnr.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtkxugrhsd.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtifzjiiof.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gthssfsueh.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gthxulzarb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtwfsxoyvy.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtdwoeplws.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtqzrdlwdv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtuuroyqvs.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtumyvkdgv.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtdfwwyiuz.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtaqyiyttv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtqwsssmfo.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtchiixcti.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtlkqktdqo.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtpmrtygkx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtfiijxxry.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtzdtkyaug.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtfxqivpyv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtoffbvgmk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtmlacnfnm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtnroifxmj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtrpizzkus.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtuthgmbrz.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gturhijzql.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtjhfbtbuh.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtmmyzkoex.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtxujqfkrj.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtjfunsqrz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtfefaksor.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtsapoenvs.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtpbosjtra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtluqzmugi.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtyiczuuxl.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtcitlvqfo.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gttifqvybv.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtsgwflutl.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtjzekhuzg.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtipfuqqyk.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtubaujvkm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtxskbomvi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpcarnnk.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gtcudbcwku.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtsnwyxwmv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtaakhamoz.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtwsxjusdr.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtivhvhasn.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtrxchhyzg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtdgtmvrny.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtvjrlqbeh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtjixuysqr.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtbzqbwjyk.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gttchinylm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtrwqvhvld.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gttzmwiykh.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtevwebdkp.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gtcgjdwdnw.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gteloqjuue.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtyetmlqbq.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtshhupurs.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtzuyuolnm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtfnopkywq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtkukkognw.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtulqlbdhu.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtasdwmyty.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebmimmpv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtsmqjzkke.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtinbzkqbm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtrafeedfj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbbuxiwmy.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtgcvfpgox.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjzzsnjao.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtjbebcxno.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtulidhltl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gttahcsljs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gttvtiojfo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgaqinzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtoppuuihg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzosttvsa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gteggtvonl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtwwfmahxd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtpzuzognm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtkqhxirpy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtjxvxfete.html


<!-- 参考信息 -->