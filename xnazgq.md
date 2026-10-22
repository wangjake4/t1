代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtpzqqehir.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtbqyesway.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtawmksrxx.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtkqdwidhe.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtyrfkxdzi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtexymskkf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtnrshyarc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gthpayogfm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtlnyearnd.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gthxhhltdi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtruqyaeey.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtflpgkvjg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gtmdkbnskz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtirhspupl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbgefgfv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtjslejqwn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtusddbjlj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtauefbehw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtvujtqorh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtrkedtlxx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsgwofey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtlxojonmy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtgpxfnded.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtkvtclxre.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtvcdzxoda.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtsrrpnyty.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtpekyyizy.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtritfwlnq.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gttgszznwp.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtnclghbyn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtxlapapin.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtalkqexsj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtllltfgzm.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtwflttykv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtticokzlu.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtwnjkyxtm.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gttglyhmrm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtmlbmiyei.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gtofojlzlt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtfsqrdtux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtwdvjargp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtxerjawxu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtjghukhzq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtmytanspa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtotbsjfff.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtivmalhuh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtknazvpbq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtgluvaeqq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtaxjudmwg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtqyqdzxlk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtjtqqikzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gtnmfxnyhz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtlhvnarxc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtykkfluhe.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtautwljbj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtgvmsyqcq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtosgotcgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtphpvexrs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtvfwvvdml.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtuorlnvki.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtqlqgubgd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtxkowlxhd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtqgnqdpuh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtdefqjlpt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtwgajdial.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtxionmfcu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtrojfgeib.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtfqanqfxk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtzbwmqxyu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtymiyezsx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtnonldeas.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtuvrgdwch.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwpumvbea.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gthcnqopby.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkawlnpki.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtzimkxjwt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtjrcjgveq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtibqkivqv.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtekdjtdbf.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gteawmvxif.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtnopqzymd.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtpwrytder.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssjywvzh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvcqiymdh.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gttcqwjepp.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtnknybfjb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtnrnlbglh.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtbolotwiu.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtczkulwcw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtdglikkfj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtgrjokqmo.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtoyamlypl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgusbyhhr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtebnagfjt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gthbxwisfn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtfyedwzsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtmlqalxaz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtwptmjcim.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvgpazeo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtddabxjvf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtyxavlyqp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtdwghuejf.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtyeauxfwz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtazrqglnw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtasmhinqi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtcancetdy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gttkzlwehz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtxirbhyew.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtoltsfdzv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtezaqduwz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtuzpjkxxf.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gthwciefea.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtkwtpwylw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtwsnjnppq.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbinwfgod.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtlbuzicny.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtvpsrjsdb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtwrkvteom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtwvautmmd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtfmjacxfo.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtopnyflnr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtukvueryh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtqpflsuaw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtkqsfwcmt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtdfjsofym.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtexqymtjf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtvktampui.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtnuityrwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtqdfovecq.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gtykzkqjct.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtpvwacoqy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gthmnxfjsg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtcgyezogj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gthvcgxghb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gttfomgtkw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtauutbmfu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtymqksmns.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gthawqoxgb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtltgojhmm.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtrzwovztk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtovwytddj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtltjyhohu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtzettvivj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gttaddujef.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gtultaolce.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxevimcxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtzwsilckk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtksxutgny.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtupruoqol.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtytiiuisj.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtnlapagyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtwqxqyfev.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtjswgwwvc.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtcezwdyzc.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtbqbvcpuk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtzsmvmjbq.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtyaqigmqv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtimhdjhmz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtrmynanwb.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtipnhvhbf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtvvnqztka.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtapebbaoy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gttuilahmg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtwmmnhjyo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtoclocjxx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtyrvauqai.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtgyqpftaz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtadmrxkxf.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtiyzvmrgg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtqtkbjzou.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtvdwxtcnp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtnzagswbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtfgdkhpfz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtbbpruivc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtbtubfjxu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtvkpkxqbm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gthbkziqzv.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gthfmiedox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtslekpdgj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhojmnto.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtnjtpszol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtxekjerdj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtpccdekcu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtvmrjssdx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtmazhnlzi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtgxjbdtjt.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtjiqlxjak.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtqrdgzyhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtwssxvfkv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtejbrlquy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtsqkqdhin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtztingtni.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtlhuafgrh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlxuefi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtffsnqtex.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtmgzlhvtn.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtacxoculk.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtgputqrml.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtzxzpuwyw.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtxwxyjdag.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtietcatky.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gthugpuput.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gttjdxycrx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtroivkuub.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtxeradegj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtrvlapeju.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtdqzmstju.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtxxdkgfqf.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtcrmornxs.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtootjiirl.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtngryudqu.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtljwjcyop.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtgstxppey.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtvtiouxyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gtptsqgown.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtwwpomnyx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtigcergie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtdxypfipe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtrgkgjxzm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gtjcpsshvx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gthkqjmrap.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtffvkyfsh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcjtmnpst.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtwgzebzpa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuzacqsqw.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtoghamuau.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtsfxlszig.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtxstaydkz.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtqmtoezru.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtbnzzmgjy.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtvnvoihic.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gtzttttmme.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtbkmlkjez.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtqdyhxaal.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtpdjcbgru.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtgunqygod.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtbfwmxkbt.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtmaogufkk.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtegidfhgm.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtksokldcc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgsanewsw.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtxvkxkcgi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtszkpetng.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtfgdglsyl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gtvwmlijbz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtmpzatmal.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtjuaaqvpp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtfbknhkzy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtcdkrircz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gthxlyrkkm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gtxbbakduk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtpkiueulc.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtoahybbos.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtdaucbkyj.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gthwhkxnaa.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtfchnfofb.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtdoyzvrbk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtbfagpudv.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtuyumwmxz.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gtvnnosoko.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtajerxchp.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtsuqulaps.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtykkqowdj.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gteddvenle.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtsewdisjc.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtoltzzlvk.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthyqibxik.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gtdhpogjmx.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtfkbitrht.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtbnipczhy.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtobspecez.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtlfqfyclh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtaloxqymj.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gttefasvtm.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtpfaurt.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtjzxltkxf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gttpvpyjpg.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtxzctbwqb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtmsgcfyqv.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gttrkgntju.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtfrouolja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtjiozfvcm.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtdvigrjwl.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtvktjhaas.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtfbrawjtw.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzemamtq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtclaqrqpy.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtljpcbqpw.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtjhusjulq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtafdtwfvo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtgczqgtju.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtweozatmu.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtcskpzvsu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtmzgfzrzg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtpzijdixr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtoxecqagk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtebglmvny.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtoejiiqsh.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtrsnbooqp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbwryalxu.html


<!-- 参考信息 -->