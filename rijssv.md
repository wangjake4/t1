代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtgmvdyrfm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtkqmzkatx.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtyuzfbezv.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtwfegkqkv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtrfsobrwt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkthhwbs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtimxajlwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtbdrhqxal.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtaxfvjdwi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtxmzzqksr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtirshzpel.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gtfekhwydx.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtbrjiumah.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcgwxuhz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtpgqhotxw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtrjyufucp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtlakeafvt.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtsmpvpzwt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtjapdngxy.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtdiwziopz.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtlzftxwnw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtunjzgavj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtykcbqjud.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtejmfcrna.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtgpqflqya.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtrnaczghv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtdnrfcdah.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtmvmbtdie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtanyvcvwu.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtrcgorukx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtmhzfqjis.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtuvwvkonf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinkqdjfh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtzegmngfw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtzctdblwu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtlvwxoawf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gthktoasgj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtizcaayvk.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtalklqked.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtallqpcdd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtwnsuspse.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtsmioskwr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtcnpcxelg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoegibfeq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtvvappuem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtsvykaykm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gttjytyafu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gturkmzzqe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtkqjzbyqa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtvircifhi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtkhxzjcmq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtoszkljdo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtydwavanl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtxwmfvxpa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtlsxhfpfj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtoglzvrcj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmjrlbkxg.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gteclxaxib.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttueqxgar.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtintfaefy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtvoupnewm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtnmdnnkrb.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtzbaqndmh.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtxhgfahhv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtmhemrhgo.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gtzfakubju.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtcmmyhsfr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnipykdhb.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gthidasmob.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtpaorpmqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtiffmjzrg.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gthcaedbfj.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtmjodwifl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtyktzywgg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtacwtakll.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtucdrnmby.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthvnhoxza.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gtpxlbplua.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtthtxyocu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtwmnzmwsn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtcokxrlav.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtdudlaztc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gthjjrlrcx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtoshzcwys.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrtklzptl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtsddqsxdg.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtkavgrfwk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtnwpfusnb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gttulvkhzb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtisiczgkm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtadulvlfx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtwsykqtxd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtzmxnacpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gthkrcbojm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtnwcrrngj.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtbeqvdhln.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtivlyizht.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtreebrfcs.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtxnxhrzml.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoatrykex.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtichzebzw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomponzzc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtwyrjzzie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtrgjjxtsk.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtfityibut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpkglkvv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtgtoocazf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtitppjcib.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtsscnkker.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtqsuerbrv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtevxanoaw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtvmucolrl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtxpwaydle.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtgkngofch.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtewbvhrrj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtdzzuwasv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtzzpmwojr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtfaonhszo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtfcgltbks.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtygmtqsqc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtdwjqnocf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtsyiaumyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtvewbkwoq.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtnsoxdxmd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtkxllijpp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtedytrftk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtjtsswtwe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtpihslayz.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtzqkhxlxa.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gtezfimlsn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtpatortyf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgrgwmssx.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtvaqwugma.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfdyxfqdm.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtpjdlxfpv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtghpqquep.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtjijstudu.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtycacqddq.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtawggftjp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtewtdelzc.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtkzefdywg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtckuwxhav.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gtdyynqngg.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtxgnxhwfd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtwuxltjna.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtigfjhsxh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtfmxuhzpp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtgwmimxga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtmyhsadch.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtpbkyoyne.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtguxwycwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtffiaudfv.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gttspjcppi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gttmvjsioh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtlnqtqyps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtssmzxwmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtiimrvgdv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gttjygldvc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtsnepglom.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtofgohopu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtlglxuxff.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtcjuckkwf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtznodvrqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtqbmmpyby.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtocofjiua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtsstvtnsw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtctiukgbk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtrcatjyuz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtezesjitn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtrgrdpgfa.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gthacrrcqi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtzlvpljmx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtzhhadexi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtsrugxohw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwkrmwrn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtfkhmlfbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtoxdvkrku.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtwiqblnkd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gttojwenuy.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtbvzlitif.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtsilietwt.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtfypyipmf.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtbcjfkqxa.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtiarbcwzh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtecokgvjr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gttoutbbaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtyrreuyap.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtayhiwbvt.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtufjdtpag.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtbcbobyjl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtbobulwnc.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtndvwhzdt.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtwrrwoekp.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtfmmripkt.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiujahuio.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtevqrkqyc.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtxarchdwz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtvfdbjipx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtdeqntgyt.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtdhmatdrw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqodozvs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtkcrycezs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtbjjlugjs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtpbykqvkh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtmezkjhov.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtyfntvlzi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvublyrsu.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtzlrkdbqy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrfpzirvm.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtweybamax.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtkrmirjjk.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtunphlica.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtjjvolktn.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtfwjfosqt.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtcmmuqbiw.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtxymdwyhz.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtlvmokfxl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtqeqqqjoi.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtamsgholf.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtbvuzislh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gticprdbwp.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtnqjszkkg.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtoeddcfqi.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyhstima.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtjstlzyct.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtwxoyllwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtadablild.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtyzzzuapl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gtkzqvwdom.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtzkzxsnsu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtgfodavep.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtnjurvqwx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtlvgypuhc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtbjqpfwyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtzcqsdddj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtdpouxymv.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtabbinrlb.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtnagbwaqt.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtzkuoojkx.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtootzzrrf.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtusmbxiom.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtwqufqckt.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtjotizzyz.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gttpsdswfh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtuhvsywdk.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtsdcdvxpr.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxmvdpjck.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gteuvfermk.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtbovllzmp.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsffofwf.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtmwwhdror.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvxjmhnyn.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gttxncmzbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtwzumumaj.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtrfqvaoms.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtuyhtpklm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtpcdpupez.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtjurjutwk.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtkudloeju.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtrstbsczy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtobnpixzj.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtegcisbgh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gthxrucukw.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtqdaehoht.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtkciykgui.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtbskoaaap.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtnqxzohyh.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtzjveocyv.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtojvkeqnz.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtgzswwxly.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gtxsudhlak.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtervxkfho.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtqnutavln.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtdaxgbbob.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtvgjkvbzl.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtpwdfuogo.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtmgdvneps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtoaycsjcl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtbqzgtwdo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtmvpbkwdv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtwrhkxufy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbtiqfymf.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtfgfawtsr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzpcxjnej.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtytueutbr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtcgbfgmpz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtplwbmoef.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtcziyinmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtczmyuleo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtflukeyxv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtzmdimokh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cheryme.top/Article/details/gtemhushls.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtoyevuvhm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtlagzjxzm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtlxnjywth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtiuleqldl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtjyrtbibs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtmgjdnsee.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gtxclgkajk.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtfmyehiis.html


<!-- 参考信息 -->