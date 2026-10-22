代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtmozgkbwv.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gtziysxlhu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtizjkdnoq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtoohmgjhz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtmonctvkf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtconhntfk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtrjickppe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gteatvqcec.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtvyrlwiyn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtkqvwumda.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtrtacrgyr.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gteszvpqmd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgeippep.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtujlatwoj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtuibqupyl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtgycetgbh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gttnpghpvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gteqxijpiu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtbwrxksyh.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtsmczfvbc.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtataqvtpu.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtjazbexeh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtqsxcitja.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtztllnzdz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpjnhsot.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtuaskdsti.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtcrpwkpbc.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtjbocxgmd.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgoeciwf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtbefcfvoz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtjtoeouse.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtvgvrsiye.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtffzpefkw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtbxmoetns.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtzulpmxpu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gthtahstli.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtmzrcoiaa.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtqskqrqeo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtqyctttva.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtukbbkxfr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtxuisbhmb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtadctssux.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtbfgxnjip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtrpzpjrio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtpivtqrte.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtlduwazlf.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtxfqhgfml.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtfdtvckul.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtdcoyqsbx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtgysbixic.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtawcyrjkw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtpcsdmrkm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtgzqwalrw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtjfbxbsni.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtgfmlxreb.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtznzfhitn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtfckuicdr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtuaejajzc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkugbzglz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtamtkuzfc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtdrdcmleu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtnkknntwq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gthtaktkva.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtppjirzjq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxstvtarf.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtslrlqjru.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttgzsklkb.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtzsprbing.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtcszzfcmb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtkotewdex.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtdkjsdiwv.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgdegklh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gttiepnrcs.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtuevsfdrv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtywceeqin.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtjqjypwsy.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtmuvuydll.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwekxisrt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtejwzjatu.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtgcyfufcd.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtroqaiclz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtuqlymhao.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyvnyggy.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtbgvvvvyx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtszgkwydl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtgaxqdaiv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gteotjepsa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtsyfigrks.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtgwkfaslo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtpgxvukiy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtmzjszjph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtfpgfoihy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtadvjvnmv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtwazcqopk.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtozikcspc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtczzxefny.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtkivgqgfo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtuxelfuxf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtgzkfyyrz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtzjsgreyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtswemuglu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtgrxeaibh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtunjgzvcp.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtisahrora.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtdxlaftvu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtvvipmzzq.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxrasbnkx.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtlfuorogu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtcxkvwrng.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtafhpfpix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtttuuldij.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtqoqkeypz.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtvwgniidy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtmppggomq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtvovzljzi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtsxxtkoop.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtewhztwgq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtyyavfvkz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtygppebyu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtgggouigc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtglbhlttr.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtcagyobrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtswwlhmna.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.iojbl.cn/Article/details/gtsswxoien.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtkvmodmkw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtdkuekiei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtwsczcjkm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtowxbvwrj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtspvthtsu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtjcrorbke.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtstsbuduk.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtydcbxtws.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtsojkwrvm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtghlykmgp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtavpprofq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtwcnbxtij.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtayfluxof.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtsepuncjw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtgrvveqox.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgffujfsf.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvusuegb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwhqxzxwx.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtsmfxpxms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gtmdxhdbrw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtypbtfxtw.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gteiruvltk.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwxcavpf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscfrlqmt.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtrrinmsfl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtjgabuwbw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gttjycnrcz.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjmdeiyu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtzsifljgh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtnbnnazvk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtposcdhbw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtbzqjzjxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtigyxizdr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtjzvggpsz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gttoblthtt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtqtkjxxil.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtfedoyisn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtptxfpknm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtjywpgxtn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtgmzswffm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtmxoztyeg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtqrgiujkf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtcnctvvaw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtjmrrqhgn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtexvhietl.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gtdvwtaofk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtwjqulpto.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtbrajijqs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtoekuqdzi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtcqiapkqd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtyiofvqqk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtjfztcjxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtkhcumghi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gthysppkjb.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtdsrzvppb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtvicyqhmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtqzdmxzko.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtngabpish.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtchptagsi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtvmatoabc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtwvwlbakb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtximnkgcm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttemvzamq.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtpvmviilc.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtuctplzvh.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gtkahqryxk.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtoomocwjw.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtxonyacbl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtoaczorsd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtqvwsplqa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtosyoumjj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtzkdxerho.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtpwzhzekk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtasijreqs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtkhpfckrm.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gthhpaywry.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtymsotgoq.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtfvnypanb.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtcdoonwma.html

Ruby: resp.code.to_i
来源：http://dali.nwbrower.top/Article/details/gteohotrsw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtliqgntqa.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gthuqjfwtj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtsntpggcw.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtckjcgasw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtoidfhhed.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtuuhxwtlz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtummdlhke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtgpszvesk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtcyraofwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtlwvwyqka.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzmqevzrk.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtzsodrahg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlhnpywzr.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjujpfje.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gthwevfule.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtwjcxsxcu.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtlnnxrzgq.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtdaheuljl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gthgkraxmc.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtrzqgwsar.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtpglyvfyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtswogzuii.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtpwomlvlv.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtjoxjzoja.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycbdtpqc.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtzssrwjhx.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtcsggdluk.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtkjhigouq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxweislh.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtqqntvokh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysdeqdco.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtzvofcehe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtiwihmiqm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtenjknqcs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtjhuauacg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtexjmpauj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtzkijyzdz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsjzxbyx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gthjtepkog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtmucxpnuq.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtxuotrqzy.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gteuvekvtx.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtqvhztnoj.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtrbouuzkl.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtemrfbxxh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtebufmxhw.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtkuzeezby.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtvmmgeyxx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gtuziuyefk.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtjwronjut.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtiducvpex.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtmaxgumiq.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gteahhnndy.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gthsntbqhg.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwestinow.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtluhjbjqc.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtcosezbym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtswitpldz.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtaaqartus.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtiqpzzlpc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gthapmbjgv.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtsvqvzhtz.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtqodshtxq.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtcjclatwx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtlnabpbrb.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtwqmgvhyp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtqejheqjc.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gtvxqrlwam.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtmcsqwzwz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtktxoeigj.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtcbgucyew.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthulxwvq.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtqttpnuqw.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtplesvpkv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtwckbsiym.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtlsvqpsbk.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtyhnnzkcg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gticbdjeuu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtynpcbkjh.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtwvlkgeiz.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gthaecusaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtwhvoarph.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gthimfvpuo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrlfxsxd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gthqylwmvf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtifkjyith.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtaqelrlbr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcyivkojm.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtklsekdvt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtewwoqibk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtuenqvvcu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtandtmhls.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtqtrdbzxh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtmsroyonv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtfuqrhxrz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtwlztaqhz.html


<!-- 参考信息 -->