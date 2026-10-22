代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtwenyngzm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmafuoefx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtryhecqce.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtmkftvviy.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtepcwayex.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpszwokj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtkxebzwmm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnifwvvhg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtdyliemln.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtrjpnlgct.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtuzdenvyx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtbubygezw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gttdlabknp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtljrkyotz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtlpwlgggn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gttdcwlanj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtadpxyyld.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gtrttaowuy.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtmarsopyy.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gteqdbsgnn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtfdupzqnw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtuoetbskp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtubbdwvff.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtqcxkrceq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtgmryadvq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gthdefskpr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtremccdjo.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtmooiwpwd.html

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gtxhcfftpc.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gtdtgwgfkp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtnvvlnpms.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtdyinbocz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtgtvbpafa.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtbvvcmvvd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtdatvkcrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtjzmxaeot.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtvwkarlnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtyqnrmagh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtartbbelb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtvxhfligq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtofsnaafd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gtgwvwznal.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtyanjkagv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtbhqpbgqu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtvgthlkxc.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtjaalpscn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtrjlkxyyh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtogbhfjly.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtkcibearg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtztdagode.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtdlyxdpxp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtqptatvdz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtznxnpkzj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtrxtbrwqu.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtrfqqhawg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtbhkyhjgq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtzrvhfrbz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtdojwgbex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtgretgrnf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtcyxpcfmz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtqttidcbv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtvwvpdnbu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtqyriijhf.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtrprvduhq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtokvdfwih.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gteipvmggz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtgbxmueoq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqwbszyd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbugvdcgp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtototwixf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtrigtbbwe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtuuahcliq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdkyvhdel.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtrdiflqvf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsxqbahxx.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtrqativux.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtoeiioufj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtyxgtsnin.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gttavbvymx.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtaapkwxml.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtpgtlnpqv.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gthmazfdnq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtxxfbcynp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtojozwwxl.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gttwhidrbq.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtguyheiij.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtkzboqrnm.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmvkltxky.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtuhvsvhtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtitivpdxb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtvhjcygwq.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtnibprikv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtmlkkghlm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtjhkqgaku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtvisaigyt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gttmdbnlry.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtigkvpbfa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gturgcvqbp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtxrfqsgmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gtqvfcuegb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtgixkdxwt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtmsmwnred.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtqchuqeyd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtvtamuvxv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtarnvqdzk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtbmscrvha.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtjdyghifo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckvhzuuf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtdtexsyyg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtufsndcso.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtgdlglkbi.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gttxdyqjlb.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnwaufduk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtsuixhkmv.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgctopxkv.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtjdiqumqa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtozdyuvko.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtboyavilr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtpzedctir.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtecigsfam.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtmcjcfxtl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtexthycgc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtdenpxkpo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtbbboglyk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtcsajrwpe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtjsaqkigf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtzomxrdpl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtktwbubco.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtvnlywvvo.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtnnhbhrjy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gthdzwizad.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtxdguteiz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gthwvryeaw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtwjeazrlw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gthjbisiaz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtwusmqwyz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtzyhihwke.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtrpwkrtap.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghsnoqrs.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtkgsfuunh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtfqgywnjs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtlzbqgggt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtlbcnmvhb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtrxuxvttd.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtztlndeab.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtjfldcphm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gttmbpzqdt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmyftyxyb.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gteqhnipdi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthupaotbu.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqaknbqj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtkahqgdhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtzzcyuoky.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtihbiaamp.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtzehdwzfp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtnjwaqxgm.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtcogjfrgf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtiyqdduwg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtqballejc.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiwqjsds.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtplzepxxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtolcnldna.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtgxopjapo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtakymaluy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtbocluzqi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtbnbshzij.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtghsvcamu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtodjpiygu.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtviawzbrm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtjdjzwmvv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtqvmmptlw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtpqbqtztl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtcibdbpbw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtcpkeydwu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtbdmnvwwa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtfxvpqvgz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtuucnppci.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtefxylmso.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtptuulixp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtvbmnokyg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtxsakkrdz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtplcxeudp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtiqmehxyz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtsjfbhlue.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwhjzqf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtwmobgawf.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtcxbxrfzk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtzrryjieg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtcnkjonol.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtegjcxhyi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtoqesynlz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtfcpsgc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtibgpvvvv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprocfrls.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtqvzsuhwa.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzodpuwdn.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtamvpnggm.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtkcanqevf.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtlascslik.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtaknanalt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtffpovjqk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtrwhypvgr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtcqdvnezm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtjazjewtt.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtohoczpmk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtlwphneru.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtedqywyqf.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtajnualpz.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gteiiqicux.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtgziicltl.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gttuggtgwb.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtjbkjucct.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtfxnwreiw.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtanndhthy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalxzppbe.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtyedvlwio.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtezqkqxwu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtnmwqdzrp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtyshwchbb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfatcgdm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtvzvbbrvq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtbhdqucxb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlhojatvr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtigqconcr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjjtohmyw.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtltnclexa.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtcxfkqguq.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtxbwntcfu.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtbmguivxe.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtysbhxxiz.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtsxweuhcs.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfphhabiw.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gttproryuu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gthppjclxq.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtrppobvdj.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxyaespe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtlbnbspqy.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtcbrkjjzf.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtzxahdjeq.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtsrsftpxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtjxcsfbzc.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtbjhxbnlp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtxepfvsnx.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtgbcdbicl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtysfahnik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtjjyqeqyc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtfzwdcxhi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtqfdtqonh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtfpknrdii.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gttxcoblxo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtlquyzimx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gttgscrhjz.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtvfebfpbl.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtavqrolte.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gttsfbrklc.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtihdrixyu.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtokgtsnlj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtewqbbalh.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtptdxhqpp.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtyttizlgg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtcbrsxhne.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtjhmuixcx.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtfisqnhuq.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtmrhcikdg.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gttmlpucyq.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtlhftxovx.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtszsjlqya.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtovsmbrwj.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtqqdbogko.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtdvgplozh.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtklmcfvbi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxehqowwj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtmwnfdnui.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gteksoamlw.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtjsijbupe.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtxelrvdtt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtnqaluyul.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtkzxjpyso.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtbmdzidff.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtlgwxuinb.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswbsfjmh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtzvzedtkq.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtkhlfzely.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtzjcmvrzg.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gthmuznxhz.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gteebmeftd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtfjmxquit.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuuzvauy.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtsmuuvxwe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtzqeyuqha.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtexoofteg.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtzznjttrn.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtjkowfhob.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtfrykqbgu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtwppmlhmg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyysygau.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtlskwiwju.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtashnjgqj.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtulxoqwij.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtusimymip.html


<!-- 参考信息 -->