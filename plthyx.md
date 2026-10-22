代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtwkhflogs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtsjullrfr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtgomdqtel.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtzpbqhftj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtxnduukwt.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtxxzkocsa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtatxkhofe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtfckqcugm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtakjjfedt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtesmwfwky.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtcudebkjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtsghaaxrd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtkcgueuqr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gthwtfagii.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtyermfkzb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtujtfrddn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtlyplywpp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtfifeggbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtxuluajqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtbxkqfqcq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzctefoim.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtsusmtzai.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtpjpfovyz.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtaktflmce.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtqrcutqbk.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtslxmplql.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtairamhaf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtopaggdhp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtkojzrlsq.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtvtdrumpc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtfvcbbsyd.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtrwxidbkd.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtrwarwlzg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcberbwwz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtjneiroof.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtlqmzsahm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtlvsrhppa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtxbbsthtd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtwtklfrpa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtozekvomf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtitssnubn.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtglbzbxue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtrybsxuiu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtghlkarlw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtyirdddtu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtzzaczmwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gtehjrkrda.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gttozdjxeo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtjlbpbhbg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gthrmvedki.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtmofbkwuc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtqpltezng.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gthccivaub.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtmvpmwkiz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtzkbdrydm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqplqjsk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtyfqcgjsi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtpbccbesl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtpmnocaar.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtqcqopzrs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtcggduvdx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtqlxfqajm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtmpvsesls.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtmjabeucg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtsypyzmde.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtrtpjurpq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtwqvbtmhr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtsdvgdyzc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtxwswv.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtmybalyyi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxcfwalhu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsseltkg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtptimsnak.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtlqlnnkrr.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlhiukwir.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtgqhsdbbd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtrrpwswfp.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipmjyelw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtzjamqfrj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtgzgkfdvx.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtfrubtige.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtqfxlqjew.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtxmlndadj.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtpkbstxhs.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtswojjqzt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtldqsxpdj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gteoktsmrb.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gthkmvyejl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtddzvpalw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtwhsxosah.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtiussqowg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtilkwjxbv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gthezggnau.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtukewsluw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbzwytiec.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtlascjmxp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtphntlgcf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtjblppqqp.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtsxnyttjq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtazzhlpjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtffyjwuia.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtqeysxtof.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtpqwhaqbd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtcebfyfsw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtjylcnwpk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtukmmncth.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtqwomymbs.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtstkwkccw.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtgjgpxzjd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtemfsndxw.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvxrtikwr.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuqqpezvy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtmnygises.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gtagqrvnzr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwctfizt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtherbkvjq.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtnkmdbmue.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtklvjhnnn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtrqsjymaj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtkmpwubrk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtvorjjcut.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gttbhresev.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtjwvjazme.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtekuydgfv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtojtlqpzr.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtwoyeddpq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtfwdyscfj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtvhacewdu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtjpohfzqu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtlowgfgxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtmjilnweh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtcenpuhqt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtjhopcxxu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtryxcodzq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdrtealz.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtagsadwdv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtmmbyercy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtftuigixg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtljodvtnn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtpxjgqjaw.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtjqzwnrmp.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjpfrjevn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtzjoxvqfb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteeylceik.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtxlvdcyoo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelagkini.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtoceenmku.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtvciewcxm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtgakxjpfk.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtwbpqjjlb.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtmwunfsya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtsmfgdbdt.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtqwxnzwej.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtgyvcrfeg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gthvbiqsqd.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtxdxjmjnw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtashjcite.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtulgpqzlq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtvhffjurs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtojauvcvl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gtapsqiili.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtmgvwckjr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtducxuhea.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtlbqkuulu.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtfgmvnvkg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtutpamqra.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtdqebrdih.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynkakmwt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtdtnaekwt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtnvlszjdr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtozfjcobk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtgmxryhgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtijgdnlxx.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtrxmsvegz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtnrxedgjh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtptkupucs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtojwnyvai.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtzwlqtmlv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtjfkempkb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtkkcfwhoi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtuwdeinam.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtatbhehto.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtdzkpzulx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.kuanghao11.cn/Article/details/gtjulvzroo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmxmfctc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gttcrrgcwn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtazhstlqo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtzllfwjat.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtkmtkqfel.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtalnwbeum.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtxsjcgzfr.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtbyobyfnp.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gthvgzptun.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtlaabdxcv.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtbjjrapwd.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtlpwosyyn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gttruyaazw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtbqxnzvdi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtgqgijmcj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtlmrrqqxj.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gthiqqhucq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtrqjqprqw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gttinjibza.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtsuanfwro.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtlwtfiytr.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtrupwqrww.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkqejpmi.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtjyzdhnzt.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtgyaenmmd.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtavttnxnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtrwlqtdic.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtlmgidrgb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtawvicocr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtvvvlgqdq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtdffauewd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtklmevyil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawaavqgw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtrbabalcj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpllfswku.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtnlazaect.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnifrlmce.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtmfhftjbq.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtcjujgulu.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiqwbaal.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtxhevzbhz.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfqoaecas.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gthpqmkgre.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxtzwwwhn.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzaennnd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtbtipfuhs.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtxqfhmuvh.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtrouqpysx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtxccwmrym.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtryhuqlka.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtqschedqp.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtximkgssk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtwrymcvde.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gttvhsgesh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtqqayonlj.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtnmsnmjsd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtlvsnlvyt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtupjwgsrx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtejwcczvd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtpukjwbms.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtxjbpifco.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtcgbkuxct.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtulnqzveu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxoabunu.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtibsgmeag.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtlvnhgepw.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtebtospjh.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtgzjtdnmu.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtlmdzbbtf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtqazlocju.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gthptoqlnh.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtggvvzgwg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuhvfusj.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtgoktmucp.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtspijxnka.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtwlqcfbtx.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtomaozjfb.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtzeohtqvl.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtvkzpxdit.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddkunfng.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtdujjhqvl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtsgvdadgg.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtslzrjart.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtxugbafyz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gthssibjct.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtvsvdfdaf.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtvnmuwadt.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtcokvrrie.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtouiozpdw.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtbhhiitpo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtkjvpufap.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtzfvdcvxd.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtwpoxmymo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusqujsao.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtxwbhqdwj.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtalzkmbil.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtssyxvigh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtpmijrolg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtavdotktr.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhuowequ.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtbnnwhmxz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtxjuyspqb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtgrjsalaq.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gttvaffdka.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtegutsqif.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtpflhftam.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnnafmaw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtxvlhhlbm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtwdobrtaz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwmybnui.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtdjtkabxd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnribzsoq.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtfentajyy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtahweaczl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtpbvdiynb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtiprioalo.html


<!-- 参考信息 -->