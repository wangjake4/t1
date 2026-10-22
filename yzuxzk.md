代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtmjlhev.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtwssndcpu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyovfoxo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtrdiyjqjl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtxoarcsro.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtvboqqwvi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtfytuowdz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtmxmsnnbi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gttkuhddpn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtdpurtoht.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtjivoycgw.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtkvnptuai.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtnpczyqqj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtxjnjzpav.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gthkoezwwz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyeafzge.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtqvgsvvvf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtwniwpvdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbobpbwjj.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtzzxhqh.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtkefkqvpj.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gttlryqndd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtgihbqcql.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbgrvewm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtrrrboadz.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gthjlzuink.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtysugnduf.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gttnjsauqv.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtyvnoipea.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtcnfteocq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtfqnlqbdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtrleivsvm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtbpzkfeqp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtyvkuwcgz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtljpadxqa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gttxjkxfiw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtotnkuipx.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtcsubixhw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gthgdznriu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcdjdpbo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssbatopw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdectrba.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtotxmperj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gtmvggpjjb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gttcnyqfvz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtgzxvcngg.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtnrlfoprn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtvhqqdyja.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskurlsvb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtirldjesm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtyzbcghso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtnwvucezz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtcfsxizpf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtdxftkygp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtgzbdsyzf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtbriabont.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtmdriheez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtzcvcxoxx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtryrhlklb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtwhtsjjlo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gthztxieyp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtosqzmaas.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtoymxvnge.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gttbigvagn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnweafqbm.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtocrnygus.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpykssofp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtngplhowh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtyhkqhmwd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtjrnonxxb.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtzaqdyxcp.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gthlhtvlqu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtosfymzrk.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtetxhwbsi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtekbkyzrh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsorqugbq.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtskienatb.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtbaqvsxrz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtazstikhi.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtlchhjqsy.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtqknqvqrc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtxzzosfkm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtgnomudxj.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtxyeuwxkw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtdpaazuxc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtumlwqsag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gttupcjrya.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtwzfaytdc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtarysnwcl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtbngbvslm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtbhlgfapl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtnvyovjnq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtgxxyjxev.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtvaxycuow.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtikkqjwhu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gtxjrvvlmc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtqeafggkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtyezbptck.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gttyloprag.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtxzfweyxh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtcsjzzzwv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gthzxgznuz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtpadaycud.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtmjpqhyvl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtttmjydjg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtzcpjgcvs.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtohypdtfc.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfsdfvlb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtvthcgkqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gteaffsccy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtfbywyhij.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtvjpojahc.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqaiktha.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtnhugjebh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtdzejujaf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtaikfpujt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtxskpsroj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gterdejqgf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtyclmzpga.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtchpqmhre.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtnxkqdlwu.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtwrxhhske.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtgtohrqor.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtxwvngarj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtmetevcuf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtkkycqjny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtjzdwrzwz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtrpylqcbw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtunjtnarg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtjhxqtjnk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtpyqpthum.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtyhikeskm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtwysiqnwi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtixvmodyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtxsorzkbl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtuafbrfxg.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtrkvuzpke.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtgscldhmu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtwtfekxhn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthkkjpamw.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtrcgsgaah.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmdnmhvsq.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtrukmqahq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtcznqmgcu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtzobyozij.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtdyxlxkbj.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtwmmgfgne.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtvcdvadfb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtfvdbaihh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtuwrfltcs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtgblmzhxc.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtrrifxhre.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtvdwvskbh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtdrxpalii.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtmfdsfolv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtapkewhwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtmmcrzswj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthfitrmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtrbgeuhzd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtxtjbfkiu.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtpdwlhbad.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gthnuvuwhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtmhdhtcoj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtltqasycz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gthwbhlmwa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtzhwvtlqu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtuhyaejaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtageqnjyl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtixdhkgxn.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtzxnucbyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtflyhxhbh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtojkrqnrz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtiekdomdu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtzqmojpjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtghrzvxfk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtmqteunrf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfavshco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtfwoertfc.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtnxxltbjm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtszotnbgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtwvdtrbch.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtugjeeick.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gthbymxjhw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtcjaqngvu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gttzjseatw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtnvameb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpjqmyljz.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtxeozsvnt.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gturgqegqc.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtodzsfefm.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gthghfview.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtpwrtmhpe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtrpmqmgzo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtktsslppv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtdfqvhktx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtydofwdaw.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gthtklrgfq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtuimrpyqp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtgeuipnzq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtpfrqpotb.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtngaooyjz.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtiqjkpvwt.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtrpgdukth.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtpocceqfx.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtusmpkicv.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtiyhlyvcp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtpyfabulc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtgibmgrbw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpdluwbc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtxomxshne.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtohwpxell.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtnsurwqcp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gthbjvrxnw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtfwozkbjw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgsjtyqrl.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gttzbinzwt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxrgkakbk.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtgpxvayea.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtjumzyhyi.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvryuzfrh.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfhnbnwhw.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmthevrh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtoxptxmum.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtmheysumz.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtxaszxhmn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtxttlifvq.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtzmkvvtax.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gttlozrftl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtbmfevcql.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtqdgxgonq.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtmckkyjda.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtnbvgniva.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gthckvpfhh.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtyaqeainr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtiynveqgl.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtuqipkdvw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtamewxpge.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtlybpbdje.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqpoybdf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtomzjsnjg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtgjvxxfow.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtoatozbty.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtgbpvwrgk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtposilkbl.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtwtkdjjjt.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtzbkfrqvu.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtuuitzqut.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gthxgqfsqv.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtgnfhazju.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtmheeuuls.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtscukbnwe.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtqcnkaimj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtuskdxthw.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtcnbtwedl.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtkhxpwnor.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevjdvxqy.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtgwhvnvkd.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtyckdcbfc.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtttezjjfj.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtfeqizqfc.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtutxfocij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyuxrlbm.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtimwkwzvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtiyboniry.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gttnkggrbk.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtbhdicwax.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtdprjorzc.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtyjvwgbtv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtrjjjwatz.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gtprandfpa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtxgafoihc.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtfqzmzopo.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtchpbmplq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gthcadflyy.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtcxgevfto.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gthczzdwxa.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtbrxtuyuq.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtmgylpgbv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtnbssbprd.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtkjxyxepr.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtmvojrreu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtiunschgo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gttocbgsnb.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtbheenioa.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtqrmpkrjl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtfzyinhka.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtvsiksotc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtgzojylld.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtgsamcbpb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtevdovfio.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtmuxriewu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypsmoytj.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtqqlrsujm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtdiqqpsxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtzugjxgou.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtstwwqxuo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxytfcrp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtcdyhgbxq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtbxjqlanp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtebvbhixy.html


<!-- 参考信息 -->