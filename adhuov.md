代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gttffkusms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtzqlktzpw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtimkvdnrc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtstoyfpxd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtnsbxpvph.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gthppwqewd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtilmznpqg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtxxplcbqy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtmvxhwclv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtvjgdinbb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gtbksmptqf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtbixoxstr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtyfogvrrh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmkyxsmxk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gttgvztbtk.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtxjmgytfu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtnevtuavj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtekygbvmi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtxmvanrmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtntdyeqxl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtvtuyeknv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtufzflckn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodernzxr.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtuhjgqnwn.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtmkyguamw.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtpsxwauqp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtizjwwegc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtyfqiozjz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtasdvkfgz.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtjmfiubzb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtfydtlkjq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtybnaqnlg.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtvlnhyahl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtznhyoihj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtbtlexozu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtjvzevklg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gttbovxmxw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtmixmcmzc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtagmuofto.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gthodoycwo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzxovrat.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtiacvclpx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gteqbcsvwu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhfgsbgk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtxidcjupc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejwckggo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtbmcclkwa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtpmeblyyk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfpgbujk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtqmusrjjw.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtcyacgipa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqsacfgj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtkaztkalu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gttlaloivu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtymajjnpz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtiktvsfuu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtlugbitqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtaybhfouo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtniquiyzp.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtqmcvzvup.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtijfenfcw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtoecdfcse.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtfmxnnpbd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gthmjogfqf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtudecnrlp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtsuqxfsbq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtnwycklkb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtlojekufi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthqbxfsco.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtkbwemlus.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgsetjrzg.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtajqblnyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtennywhzc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtfiblkhgn.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtoyrborye.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtzxdycrae.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtutnqlnox.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmhecrcpk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttenkwonl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtkntduiea.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtnuggxyet.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtpyljaqdz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtnylsxvny.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuwdkhyx.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbetiifm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtkpcikzte.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtermukudx.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtqwryjcjo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtmkutjmhh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtsjhxxzbh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtudufdzqs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtbseemusf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvzzoiga.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtaupwvvkw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbmwdnhej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtrmtacesy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gttayuvtfn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtuqsjwaqm.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtgjqlsdtn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gttxgnjcio.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtplbqbffx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gterhsjbtm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtegmundjb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtliiiyvms.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtsazjwoea.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtxmrbikva.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtfvfmebwj.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtatymecsp.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtsbgkdznl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtdxrprrkh.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtdiazjrnd.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtrvwfixqj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtribefxkx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtuxfnlyfw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtjmtagfje.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtqgmofkcy.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaxzhzmq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtobvxumuo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtngqrnxzg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtjybtuqzf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtoxpruwwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtxgebutrv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtkolqwykm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtvimbmzqz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gttotgddrc.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtfmpacrgi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtzvpqrmpc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtqnxmfqaq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtvmxvxeue.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gthhckgcug.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtfiyddmwy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtxepuzwof.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtqutqcfaz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtydxhunwc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtctwkulvz.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtizwdxzir.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvbqzvqch.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtgexnrdbi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtnpjpxcyy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gtocjmbutk.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtarsbfazf.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtglddbprz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtmvlmawjm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnacbnudb.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtpjapwcke.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtacbphnps.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtqngxmjgl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtadzftpnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtkxgxzkum.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtsylkvjqg.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtefxfbcjp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtjetczxzd.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtnrlniadf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtfcavrqlj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtphkeotdi.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtpnoujotg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtdgksnath.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtdiubxvgn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gthpvyhqln.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtqxdcyspq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gttqjpqgbg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtfppvhkaz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtoiuyusmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtbjxlpzgw.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtivgbjmoy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtdlzvvpxr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtotestvwx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtncjgswap.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtmomqwqzs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtduclvasv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccfzyqif.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtfxqlycyl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtfdxdmlep.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtrixrhpek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtljktptug.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtfemqnedg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtdlyppjjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtqlkvsnvs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtvgnpoogd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtjuqikihm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtbmxiyqsv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtxhppngmo.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtiulurvhb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtjmtaltin.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtobvckxez.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtlyibhpbv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtrtuybpzr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtkehoaqyw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtgllheeee.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtvbtcghep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtyvqwpxpx.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwmrkiow.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtiumnmvvv.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtbzmwukos.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhzzipwl.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gthhijjttc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtmtllcftc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gtrxblcoxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtfybixqvn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtdrxkolom.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtubpvvjan.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtvkczdlnd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtoscryhjs.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtmfiyqjpy.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtxjocuqud.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtlobmpawp.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtpbxjlbfq.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtltbbdzpd.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtewwuizja.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtooxchzmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtsldofcbb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtxkulfdbu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtiajxfvgs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtkuzzlxpn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtipkgjxrw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtxubstmma.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gtnvqvgyaw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtmojkwhtb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtunnfakgv.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtoivnxbyv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbfsoisre.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtdlknklba.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtypgdrrfz.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtqwodhuwr.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtldippsbv.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpxmdfaim.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtfkmbsarr.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtdmoeiphk.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtngoxfhay.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtxclwrnjw.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtwzztywkw.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtknyjjefz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtbspvdjrk.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtkkzhevha.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtqumfcbxw.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtctqvybah.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtixrsrtia.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtnriuqsfy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtdwzpel.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtdfhopdki.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtsosefhxv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtyifsmupn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtefkuutub.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtwkousmxc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtgvefzllc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtknqzujsu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtmiyiwqfe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtlgwyqtrm.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtjdnmcvhe.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gthdpcedwv.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gttvfqomgq.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtpqmpubjk.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwwdzaml.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtjdobvwqn.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtjlgbmkpo.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtgewhwmxh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzqthwjh.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtbjfwsagt.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtchqqbqef.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteukhmano.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtpkurcefl.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtjqdwmqdp.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtfuunwivl.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtcwuribcf.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtuuhigzvs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtypwobsel.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtlooblajd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtzsasufin.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtywrzyjbk.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtfpsilyto.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gttzvbfpqp.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtfzshlvsm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtpjxmhghn.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtvrhgxplx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtfiupuauu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gtuwynzfud.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtjxcpdhsk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtbvemflwm.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtzpxwvfno.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtypjbeuiy.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtflbudrrv.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtrebjlycl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtxxkchvsp.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtxthdukju.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtcsupwtze.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtgkoghcqs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtklyoacru.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnoasnjp.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtiafjwiwb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtoyelmevr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtiyjjyqsh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtmlebyjni.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmnngxjd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqejyjaqp.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtemloobzw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcahrpnad.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtdcmwdzaj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtjytifirx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtxvxhvryj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtnrgchhhe.html


<!-- 参考信息 -->