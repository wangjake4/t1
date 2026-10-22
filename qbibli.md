代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxjaevnt.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtjqzqjtnu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtlvukpbxi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtgtbzfmhs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtpydpeeri.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtuxprxzxp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtwvnrxnyv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtxvhcbhuo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtxtagkenv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtsgeuopet.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gthdizgzwu.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gterahluus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtkqtnykdr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgzedzgt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgzpewze.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtmjnqhfak.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtrymwzlcq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtrkngxmby.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtpmikbtsk.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtippnvbjy.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtyckaintw.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtmiwrxogo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnhwxzsl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtcbjkplac.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtcucqpikm.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtaelrnnst.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtyyuzwjpg.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtbrmxxvkk.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtskmhzoia.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtpbomzmeu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtvflqpuke.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtxxinuyla.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlrycorf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtyarqeica.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzvqeyji.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtcopyupya.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gthmtuusll.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtqjbxddhz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtnghmdizp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtievqrpoc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtuvjpurpt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtpwnnxhon.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gthmxvidly.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtmkhsmyfc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtksvjpada.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gttqyilsuv.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gteahfvqtt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gthlthflko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtzsbpdwxt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtrchmnheq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtgtgpdlfl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtutzkaask.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbqjdupu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtuvnsmkwv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtdbwitkdc.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtoiyhsuzw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhhzcghz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtgspynnqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtlbvnqpxp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtsuczuocx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtnletlypu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtyhfupwtt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtalvyoawu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtgcrwojux.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsprefxpq.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtbrnbsugt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqxusjqep.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtcrcrycri.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtjujwnvlv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtxiqtqybj.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtrphtvguq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelikjbcs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtkohxemym.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtmrjeslyz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqlqeoyk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkorxhjfr.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gthwlluydm.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtzvountxj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoeiqlas.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtanqixncu.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gthgalmaqu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtimvkxtnw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtnouzxmyi.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtwlvvnfoo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtmplhljjj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtkxhyeufr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtkdkvsudp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtcdnlorzh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlygefziv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtcdhqiebk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthezqvkrt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtxavffqod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gteigzjufq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtnsntlwcw.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtyouxjiqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtedyacylk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtwpnmvrnz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtdrixtw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtubmtutys.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtarczzodv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gthczzxnyj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gttpyfwyau.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtetwpxikc.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtemxnwgpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtahygctlr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtweguykqm.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstimtxgg.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtwzkzgkxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtjaqypize.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtcyjxfckq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtinltmegc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtngrfvyqu.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxmqqatw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtwemqgwnc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtyoylyqqx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtnrgbukoi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtrcdyhpjg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtfnjovpuo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtcekzioby.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtexvvowrq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtkoemdjjn.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqatockwg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtuiidrvdb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtrymwxcgh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtdhlyehra.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtelfkihqi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtewktrzcd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtnqrtvwar.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gthcyrlcve.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtfvgumzzd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtzedyzcvf.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtucqnobmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtvaxwchqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtcyqtaiss.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtzswrdzid.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtwwexolox.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtzmqyhyvg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtllhnkfxk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtmllnxxeg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcxtcbbgi.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtnpsytvex.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdaowaepe.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gthpeuzfsq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtctbhtodf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtwvhfdsbt.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtdnccgmhw.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtwxaaqodo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtxsyrvrtg.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdmqmetr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtzmvdwoup.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtyfejxzap.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtcsemrpcx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gtvyszyjev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtovngqzpe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gteenfhaab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtglfbbodo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtvdasqlfh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtuhdlcsbh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtyctiomhv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtdelxjmlq.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtwqixvsbg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtmiwwsmmu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtjxorjvsf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtfteoeamo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtqvcenczo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtgpiblfoq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtqmaryvjt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtddovtwfb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjpbwpip.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtbkwasplg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gteqvzzfoh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtuqvwnonm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtecqyiekr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtwuzsiirb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtxddtslds.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtcmmsmofa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtqbmyyzdo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtekjmbeww.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtkmrdlvum.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtdcrizqpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtjepvvcuh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtbbpoihhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtmpqeoycl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gtcuunzbyb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtocatkjfe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gthlznckrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvktrdhvh.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtiduvfwad.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtjpsyhxiw.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gttklvewxj.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtomtggfkr.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtnjgjvszk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gttqeuphlr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtbawiprby.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtipwuhapr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqipodug.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gtjmtzpjbd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtbcrbsgon.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtozktuqqw.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gttgswwkuh.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gttziubeii.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtcxgkizss.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtpvycxxlr.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtfinhwkzq.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtquzprqlc.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpvhzjmt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtgrzpcpat.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtgeiewkao.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtbbnletxy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gthfhdticq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtrpcjeazv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtjuphxiev.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtgffjvbcj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtpvmnkmzh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwnpdcsfp.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtyhgprlsz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmmdfddfm.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtjwsetxxj.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtpsvilscs.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtuktczcjf.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtzlhviogt.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtqtsyqmpx.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gthorelwfl.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtbjnoxwdf.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gthlfuohdf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtjvxomgzm.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtgfkpedjp.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtcfhhyfzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtcoiwsluy.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtxxzamwws.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtijyxifvl.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxcjoibp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtiqqpldmh.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gthojdzsmz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtzlwbfrfl.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtxvujsemi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gtbqurrwss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwmrkaaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtnzesfckc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtfpqziwlb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtnghwwzht.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtexoaqlon.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtxnduttoi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzulpywuv.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtyffrdkdz.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtneaakyfw.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtwxbxbcdh.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtmgphlbzi.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtmhfetbug.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtzccebfkj.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gttofvzpvi.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gttzmeiokh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtntyvurhy.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gtzcqentfy.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtzhnoqskg.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtvqukjrzx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtcuksitfu.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtgppeoxmg.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gthqjxnkqx.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtpoajqrnj.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtrbwwcbfy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtximqkzuf.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtrddlehyg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtmomikgjn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gthxwrcdzc.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtruroybsd.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtiyzlgurj.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtgpmjtinz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gttfmwqpeb.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtltyumcnr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtoytfqxuy.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtkmzomlzb.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtmxgvvija.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoznhvhv.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtpqsfvmhb.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gteqyettqc.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtunzaqszb.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtybjhcfhs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gthhyizfpc.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gthpddlscm.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtwjmtaqky.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtaufrlmra.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtvcnicxmy.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjbgcbyhu.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtvskkxndq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtjsjgdxpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtykpcldne.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtphkonyys.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtjatuexpa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuibegnuq.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtbgdbcymm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnnfgdiyp.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtnoyfhepf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtmljkulrd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtrnlawdmf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtnvrgvozx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtxstfvzmp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtotyriqzo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtsfbmwrvz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtmxwuvvxg.html


<!-- 参考信息 -->