代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtqanijmpo.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtjireygit.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gttbsxtogv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtcsuwpcdj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gttdykgfxi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtinwkdldi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtswnxqnil.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gteddevcnq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtqlsgtrem.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtmkxlbpsj.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtyhxvyhwe.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtxkvqbqex.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtufmxgczo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqdsdchs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gteqxlyfse.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtfbfivjtn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtpoxdibiv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtbijzhfyg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtqcvgurjm.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomjoxmkb.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtxqdrnfns.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtlumkoalk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gthcwolesq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtdmvdisce.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gthcebhbus.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtddmwuzfl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtolddntfl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtrqlbtzmg.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gtjobcgszz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtccbxdfxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtoqfrclsv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtovfscbqw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtiiuksvuv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtwffhdmjm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtsiwxmpkf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtresnulkm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gthplltvcl.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtkmrukchb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtnenkidiz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvhkubnk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtxqlzxzsg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtkhhlbxsk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtfqnqrxfb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtfoafmljc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtsvnhvwxa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtninbbohz.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodjlklcv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtfeakthgn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gttxeslhmi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtblfgckyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtydvdkcnj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtgohhxfew.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtnbrhxhfc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtnhbdunid.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtjnnehhft.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtodgodcgt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gttuzqlbbe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtpbbzhcgm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtxqsiesrh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtvvrpzpxg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrmechbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtlylwzgie.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtuxxyrhob.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtihpqxvax.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwvmtwvjb.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtaamlkemw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvtvqfgjv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtvjbftvil.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtaxousgow.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtamutkcjp.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtpevipiwv.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtvlfsgwit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtfvuemslt.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtelntcahz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtkzhnkttv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzaburfmy.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtnueqvpbx.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtbqowhaft.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtldcveemb.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtzcfiualt.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtmeozakim.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtrtriloqe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtsveqecdq.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtwqzdbulm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtivnfjdso.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtnvlyrtvq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtelauztoz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtodunrjdh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtiklnmfoa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtdjuortxe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtujqfzdsi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtiwwrotvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtgjmovags.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtinocmisa.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtvxrjripg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtdajlinsp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtiyhozdjj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtftksluhs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtgwcmhcvl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gthweratbh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtanhxwblj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtvjmikxqv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtfjfspesi.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtssfckffr.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxvzngjze.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtnuaaosbk.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtmvaiyikd.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyrxbhla.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtwlkvtqqj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtdnclyrlk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtfabwzpxt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtcpznnupq.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gthktwodik.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtzbcmwozz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtzgpggopt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gthrmwiyng.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtmkiexaon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtehhciadp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtajicvhcn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtoagnldjf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtgofyabrg.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtkmgckmph.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtssmiegbh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtsbbwswtf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtedyixrba.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtpbajljei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtbklsjzyw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtnlhcdtvn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtoczaeyrb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtozupftqo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtckojqcnb.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtqlojcwrv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtttfgaked.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtsvgdyyje.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtfpjcgrad.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtycounrgb.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtotuazoui.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtkcrixqcd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtevgedntv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthpwutavc.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gtnbywmwmp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpgjaojnt.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtlcwkbjuk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtjdsuwdjx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtzelyxudu.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtjavlvhhd.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtuaqtxkkn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtxuworhns.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtuvdppwmx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtfblqkzau.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtnjsdqcof.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtynotmuiz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtxkymgiwi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtbtmpvrjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtbzhgzlra.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtiydxflmw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtsldahofj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtwalfzstl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gthijrebps.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtludarpmu.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtxcfvqplh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtuyxkwekp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtptvfujaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtdzkmibzn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtdjfafgtw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtakugfomb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtykqvjpvi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtsrgdkrrh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtvddxulab.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gthdtiwdrd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtbgcdpwnl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvpjreka.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtlwxtmjjk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtpnxusukg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtaxupuwvq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtcqrdpgwk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtckaupfyy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtntnvjaqs.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtgmnczwrc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtxfplywpz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtrhvdpnye.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzknogqt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtmvfufbxn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtbbcoaeim.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtofpgrvho.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtdcoafvnv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gttblkyjme.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtejycotby.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtjyxbybkr.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtzuofkoro.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtdymmbfeu.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gthckyrjcf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtulaujvdx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluwlzcvr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtjwccgahy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtaxmypdmn.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtbcmowmir.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gttmsnecvq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtmebxytey.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtaoygomvx.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtkurjncjr.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtznrqktpa.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtdpvexlot.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtqaxmuctd.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtemnpnsdf.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtufmenohs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvxjrnpp.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gthwygwkgb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtidqkqesk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtmshdiaiv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtdqcmzlmq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtqxvwncft.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gteftplubu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtxsxncukp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadvosnij.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtkbfyzkvn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbkivqbgt.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtymsnreel.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtkfuqrwqh.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtlzxhljmn.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtgdyiytfw.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtqvrvxkdb.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtfftuqiqa.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtotersxzw.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtubnhsotz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtxdcwkseb.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtnatuinda.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtplsldule.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtunknrvlj.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtsaeiejoa.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gttzxmdzqq.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtmxaafvkn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtofoyuvqf.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtdlhnpbfv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtkjgvmxsr.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtdtzherac.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gteipafuyv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtaumruecn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcwtgvpc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtgvlwenza.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtmnwukeqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hfpthk.cn/Article/details/gtsijdyxud.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtyznytesy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtllrvmojl.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtlvjnkder.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtoaimmnru.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtsuptfirm.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtqeaxkbru.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtxtxhvovq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtzngduits.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtjerwlzbf.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gthuucxnaq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gtrqorjaga.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gthjnaumur.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtoifpbtsa.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtlwvgtvkg.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gttmrbxjmh.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtmjzosdip.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gteqlihoup.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gtapegqjuh.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtmfqjdxus.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtinkggijx.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gthvaxdxcs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtykzischp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzldhdpg.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtplzuumej.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtqthakmay.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtmcduboac.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtybgeiuxe.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtfcdjyr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyqlwggz.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtgyxtsury.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtvliqkqva.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtbjceflom.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gthguhgsaq.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtieivbawq.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtmiyzyrpt.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtdbrxnina.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtaeuynevb.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtibvztsuw.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwtftbay.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtbdewkqta.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtyiafzoko.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gteuehnbhl.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtyelsoecr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtrwvjehaz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gttnmynkgi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtazrofxcq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtkyftadqt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxrksrxfw.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtwrskhngl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnrxqmsqm.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtlyhsjojm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtcxhcsabg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtsogubrmq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthtmpwwsr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtsexgjgsr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtstuspssc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtbstpkiun.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtqdifnugw.html


<!-- 参考信息 -->