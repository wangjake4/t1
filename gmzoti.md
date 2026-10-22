代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtbcovdple.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtslvjyzpp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtozahfftc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtlftgrjgk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtrxzslzfz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtiwrmcpkk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtxoshuisx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzvthaurn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtllsjjqpl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtfwzyoekn.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtaubiyudl.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtgcqrktsw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtswqwktsp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtdbiuzulk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtlllketvw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtusroxkur.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gteofvslvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtzsoqvhcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtvdvhnnhr.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtzcrctosr.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtlqcntxke.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtovngmzto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtpbaycwon.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtxqxecsni.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtnllxwsit.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtootwxltk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtohgakbzo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtdcuouxna.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtayadrhul.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtyevwmgnr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtjlyppton.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtjermktgx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtnckqaqvt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtkidqddfy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtdfpneyvl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjpkhqpzw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtkvjhvasf.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtfmgpplhr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtwgzcfkhn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gthfgpmksf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtagkvipfj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtysgziwym.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtdmowzneb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtbjuzbcmf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gttobxmerk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtsocgbges.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtluoxkwvy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtjowwcxta.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtngbtkscc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gthxsvbfwy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtmfbversi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gtwamvbyfz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gturlhgcgs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtmgvmfuvh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtktfzgxma.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtfcwejpop.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtsociejet.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtdiiobmhw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtzvghnaty.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahnieooi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtvhmsmmdl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtjepylavv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtvsxxbidx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtoivhsnfa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdlxqevng.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtzqttreuo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqsxhdfyu.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtmctpdokw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlioxrue.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtfqjhfjlw.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtedsvudmw.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtfoivzqay.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtkemsvkff.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gttxhiqgwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gttujwuxwi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtwtcoxpyj.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtzhroehet.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtqigslnsr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtdavhufkx.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtpufyxjit.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtriwhfqpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtoscmdpgk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtczbakvqg.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtyzelcdie.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtjvruzwak.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtiviyvjhk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtxpyumsfi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtcdxdpthz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtevclkrwu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtoxkbfbqs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtctsamiho.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtikrtomzq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtbatjqrpv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtbzxtvmuf.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtpfeoldze.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtibvnggeq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtnozbkcqu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtflbqgdjc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtreopfsev.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtifcsgudq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtewcoahya.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtfvirvlvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtjtxyvzep.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtsbmeffms.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtrkwdiwlm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtmjfnnula.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtuiuojopd.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtyvtsuyrp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtfvbxupse.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gteatzfxfw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gttynlfepn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtgtjmhhpm.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtowtirsxj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtwbljiuyy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtahiwqmvm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtimlddatv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtkjjpdjwl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtruramdyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtpnaldpcv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjxzwxepa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtkarxgheb.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtnopuhptb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcfsfjhz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtqnlgxgjo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtmnsgafww.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtavadbzfz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtqkbckxzw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtxkppzcji.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtblrawcej.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtcnkdfrxm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtwcqyigmh.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtxvipfqcp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtujtjrdgb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtwaznhtzu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtbdewifpf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtqcwrejqz.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtpcfsqnbd.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbpbkbczf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtylwnjaqy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiamsmblm.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtcfchwpec.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqrnmbvtr.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gtvoyqauni.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtdbmsbycx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtttabnxnw.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gttoykvclv.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtoqxkjumk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtrhfvlilo.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtpnjxvugo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtgiydhxbe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtkhkuueww.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtaudxmwub.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtzfkmkecp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtnddyebtm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtzywronom.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtxkupuvze.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtnldftmsu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gthafspxnb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gticurhqwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtazrvyogp.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtvftwjayz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtxaezktxu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtskidpyjw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtccrskalj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gthkmqcqsi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxazaepka.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtkktdtcjb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtsxrmpvjp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtxjhwtvsg.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtifazaons.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtvnzslcnm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtlgszlzbg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtrgzujsgd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gteehehrxx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtbnizamyu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtxofyptbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtojlxxqmg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtbboskwyn.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtwkaguhsu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtnfyqykos.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtxvqrjbos.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtelkzajja.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtrjosabwg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gthkvcafyl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtinnjwyqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtgdbfkhww.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnkpchehg.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtgbswrqqu.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtvlkejleo.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtqzfhotdi.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtauonbeel.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtgzuypqhr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtneffbgqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtznogercb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwadntmwk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtbjpogomn.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtbzqjakhl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtrrozlzxd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtwedljfhj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtvvpuyjyj.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtkxmouumf.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtnqctbkhc.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtxgzcpvby.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtrdtmpezv.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtkdmrnxtm.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtzkpiqzyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtrtkmwedz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfcxssyi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtprezwbih.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtmmpkbhma.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtgtostfhs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtgbtmalun.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtipstglkm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtopemdldh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtscmsymsz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtbtlnoltv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzrdidumg.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzpbxksc.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtishgbxub.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtifbywqzz.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtrhibvnox.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gttdrmnnbh.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtcvsyfeic.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtshltjqov.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtsnjyfiui.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtpzkglnro.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtsgrbirnj.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtruufbmzh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtzgaqfbxi.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtoczjltve.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtblxsltcm.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtwbeivrsi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtdsbaaord.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtguouizmb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaemhtfsu.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gtjcackuvv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtwbijupga.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtjzizbkkf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtoozrczob.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtshzpyljz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtkpwetcxg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtxtjwnrin.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gthunwjhmt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtaukngqwn.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtiuehgxke.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtwzvfsvbj.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtdauyqyld.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtdorevxso.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtawapkbqs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtxfssvqsz.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilqkimzd.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljhputan.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gtbozvpwtx.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtqymxfkcj.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtclgkjfcj.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtjnpoaiit.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtgecrsxmh.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrqtaiest.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvazyuhqo.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtmfaowpfd.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gthsvvupuh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtqovzntvy.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtzxwuztho.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtuhxoekqo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtvlktmhjd.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtabrggmqs.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtfpfudzrr.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtubiufsiy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtpfrtejra.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtcxokyfxz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtmbpqojbq.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtsmwmypgw.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtukomhdaf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtucivxnuh.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtanxtpfuk.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtfgftwndj.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtngguzxcz.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtzhmeedsl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gteufcanht.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtyboolflx.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtxuayhspr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtllibbjgf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtgxyikswz.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtrdccqlku.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtbfncpdbl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtchejsofn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtmqnngcnt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtocksepqp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtotccxwhz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmiuhjkrt.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtjictmhgr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjnbutucj.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtwdvzabej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtguytcgdx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtmiphvhfz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtiuirszwl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtkyzzsbev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtqkrqkjgf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtjvgaevaw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtmqvfynim.html


<!-- 参考信息 -->