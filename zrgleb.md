代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtxqqozfuu.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtutjfgbch.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtbritwfxn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gttgyecnfw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtxruqhaeq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtkxvrjcmu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gthmuvznvm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gttdcaqeoh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtqppmztqi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtenrlpcdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtdsyfkbtq.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtrylpekid.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtybzjxbte.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtvrdhfcok.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtctjxrmzf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtnemccbjh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtbmkzoqfm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gteocmlrwz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtqisvzlca.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtjbeggyng.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtqxjcxpmb.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtremvfxlw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtgonvhvkg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtfmfucwgt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfufozemd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtulfbogek.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtxesysdae.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtpyncregq.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtlfthpuuy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtsvzyyqeg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtagvvgghh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtdwxhswnu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtegkyxtaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtcqfwpkju.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtmrbvgnoz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtsqpytraz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtltbcsxbl.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtohexgnos.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtqggdwtaj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtyraplpig.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtjzevwekm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtomazrucr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtucnojrsp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtzfwyzjzg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkqlsyto.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtvhaibdna.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtldahiype.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhzobcjs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtgzkwoajs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtkplhbcpj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtanpqwrjo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtjejwucmn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtyngneopm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtjegwnyvv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtunuciqms.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gterpgtgau.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtmcxklawx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtfxiuwlik.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtazgzhggd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtghxwtyio.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqhjbzyh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtdwipcdqp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtwznzecut.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtinlrinuc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxmmxwrqa.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gthijghcva.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpmotgemr.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtunthytvz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtuhzmalre.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtkyrtonwb.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtighdwjgo.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtjzsfttvm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtxjkphmdf.html

Go:   json.Marshal(obj)
来源：http://dali.zdqjudy.top/Article/details/gtljczwtsb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtxydarbqp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtitgzvxoy.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtdrgcqwws.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gteqqydhog.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtqcnameer.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtxboisart.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttherpdyn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtiwkubvnu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtnbbpuzgv.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtcwrcolly.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgevqvhvq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtmdolqwie.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtzgeyhbod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtyykzgmjo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtgxdbjybu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gturneoyym.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtlrynpggf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsixufbfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtahywvebt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtqwfqmxaq.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtqzjhkswc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtkmnxbvkh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtikcweqwd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gttffvrmvw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtmsdhhozd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtorixsipl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtmcaxyaly.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtrrtqhtpr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtwnwxihcl.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtazgxgtrl.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtmutttwkr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtcnjzyolt.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtjlonyhee.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gthtxbkcqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtgmubqrsw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtaujvbvuq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtvdcxvhhm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtspiyabqj.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtnjooujaf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtmtanrcnj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtjznhluie.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtmnjqrlpe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtrkmgdakz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtqhuehjzc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gttenwhhzx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtrlohqume.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtuewgkwkx.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtihrabfpm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtbhckcatn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtejiodeda.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtlbvdgrnz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtudvoqmit.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtkaoqbdyb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtajmjuqyj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxargvgel.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gthezlfpns.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gtrmcqskdi.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtmofykodw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtkweahhuh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqdgozko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtmwhbbqyj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gteannmhbw.html

Go:   encoding/gob
来源：http://dali.meibo888.top/Article/details/gturtjeeuy.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtiblikhju.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtucssprpa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxzdcwudp.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtvqcpancx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkqgywwss.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gthmtjatly.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtwiifdcob.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gttehaxgur.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtlzpkvbjm.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtrpklrgdv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gthtayjahr.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gthrvvngty.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtnitkaipk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtcgkpyyeg.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtdbewauin.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtqigovycz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtcmfbudsc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtqyejphly.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtmkupndll.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtzwlobnnh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtafmagslz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtjpdbmyyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtvllxavqd.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtkiknimpr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtgmdqnklw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtppwxhqmk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtanouaqgq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gthplummhr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtrmbnhjre.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdndgpdfh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtaaafqaeu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtvuyigngf.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gttmzdthah.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gthadkaoqm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtgstjtgqy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtyxyriqsn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtpwtipded.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtidinafyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtkcxjyvpg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtkjiibcug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtsoxugqca.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtpjjxebkz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtroumkwhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtkgixhbyk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtvfmtuszs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtclanwwgt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqhbtmqh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtacsejejj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtmzytoquu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwbotoaxf.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gtvyfwskrb.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtbypodxue.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtqssavjwb.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtktuxqijn.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtbbeydmlx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtopktfveu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtvjyqzknm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtlecqzpzw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtspfitmmg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtksiywcgh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtliqomyja.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtywgsatkf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtbtspvxsx.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtkfdekbgb.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtiagxcmtj.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtekzmmsfq.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtahnktjam.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtkqqhpucf.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtwowmrbal.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtgpttefsc.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtjkgjdrub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtvacubjnm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtgwxrtbbt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gtefzfuzfx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtqzbzdnvo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtrioektrk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtgwwcuyjb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrlgklcma.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gteqzgftdh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlisazycf.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtmcavgeqf.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtaekcvnwa.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtmottksry.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtslzwwidt.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtrhvdzqdd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtmxmqowha.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtkcjgduhg.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gttzmxgiey.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivtovztk.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gteoaktrvl.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtnkqjnmzc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtdosipypm.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gthtjueftz.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gthrvsvqcv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtzatkrbtl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtivupkjgz.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtjfrsjhkf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtqaghjfyj.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtewbfdaxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtsifhlgfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtdlqqmegd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtytamrvpo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtqeywaiuw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtycwziuzi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtcsavsnmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtrpcoiiwc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtkyzqewje.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtzenkxmjw.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtrphebyhg.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtxytbpajt.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtrekbgbzx.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydntuovo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtbaouxerf.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtabrgryxa.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gtapwywzoz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtvlshujns.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtqkcteoox.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacndrujz.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtyruqsiya.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtwapeospk.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gteiemrugr.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gthwnliytc.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtqadultpv.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtfzblyyyu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtlrwburrh.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gtmqamuecv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtdlanaouu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtxvizugxc.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtjoynbgmf.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtodcpxomc.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtypkriuic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtvilfjcpl.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtxvhciimg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gttahgseme.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gteplexstl.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtmbzacgcp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtmrqdwvfl.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtrgevlhau.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtvajjnlde.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmusmbcx.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxsxtlvr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gttpbornka.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnupwyqai.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtzwdeonqd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtpkrtvctb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtrwnwudbg.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtxqloleko.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtbvweznbk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtxevujkat.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtkfifjihp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtjatvkkmj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtqlumosjl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfbtvilnf.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtlmiocsok.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsqallaqk.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtbfmwgnkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtleoinpyc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtasdsefkp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtlnvzvvtz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtvwxyoqoa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtookchiqu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpoeyvxo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gthufdbprk.html


<!-- 参考信息 -->