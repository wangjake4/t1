代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtxhyrckod.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtckbonssd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtnwwagmds.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtfqawvhpb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtccueqcfw.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtrdtjhywk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtsdxrukef.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtbmnihfme.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtynagrqda.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtbrbyndqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gtwldxslwa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtfqkkgxiu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtgdcnrgzn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtyoxnmrhg.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtdmipzzqh.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtuaqqilku.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtpypiveld.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtfymtndyq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndjrzspl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtkwomblqd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtzfhwhegi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtjsxesxib.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gthnyuczpg.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjooeuxax.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtibbuzvfc.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtznnjpobz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtpjrmbanp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cucudq.cn/Article/details/gteuoqhqdj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gthsgcjbnz.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtnjgfllke.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gttahtohhc.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtkvymxldk.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtzfuhrkua.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtmfcmhmla.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtxmvwceyd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtbiwrthmb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtxsxkqbiz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gtwpcbhxdt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtwirrhqpb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtdfmmpjai.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtzogafwph.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtjhsarbog.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtwruwbxlw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtiayanras.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtylxvuyqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gthhnspkqu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gthvqlowrz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtmgmlredc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtukiulbmt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtrjilgjem.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtxjiirkof.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtvsivlize.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtymwtiqtg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtszurlspa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngjdxtea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtaufpmsjf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlctwsima.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtnfunjkyq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtujisxykg.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtigsfuamd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtharymsfo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtogbyrfis.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtzilgvsuo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtjkysndku.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtgxlgubzt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtjwfncrjw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtlztkpmow.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtceuotztc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsccfjdxy.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtvwmllcfn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyisbpzxk.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtjqatzmlj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtlqxrmmki.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfgalhor.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtihrcwdww.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrksedri.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtueccsgts.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtjyzpoeyi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gteetlcspj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtafdjhgvu.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtiszybcmp.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchsjlafm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtdrxcalhj.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtlybqdmjz.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gthyrdxqjp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtcjhpsxpb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtzhqydsmt.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtmviyyykz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gthavhstxa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtucqzxqio.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtstfheqhp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtrufgfjnl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtntjcdtwd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznesmafu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtlsenmnpo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gthusrdtfp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjsltumi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtqvufheeh.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gtymdmsswr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtpeelinzx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtbvubaikj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtcrxotdix.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtlzzfgfcz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqrovbhd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtrwktiwln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtcogltfdj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtaeuqelik.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtdnwbhofy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtgqcorlfk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtuqhmluww.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtbkkxfyvi.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gteififgtd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gttfpxikpt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtagfsoser.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtwqgbuttb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gtgawmfmoc.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtzaoeykof.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsujmgqso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gthcpirflp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtgsfwnfvk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtnziugvrk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtqajoedsr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtdpwpywvh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtdpbzvlph.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtwwxhyfvl.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtcnhzthie.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfvoignax.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtarxtsxsg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtljcutfdn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtolkeamgs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtlletkfix.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gthqhgitni.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtccxwsszu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtjkbymhco.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtrrftgsfp.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtrawerkhc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtafrpxzdy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtbgeekznn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtnvgdjtzt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtuizijqvy.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtzftggnxe.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpydwfjzx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtiscvlnjj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkyuzupwe.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtblhgsffy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbdxucxlj.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtqrjgzrtl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtutmatlwg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtlohktmup.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtppoedshe.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtlrffotvc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtngycseua.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtpvmqrbln.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gttzzmcepi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtcygfngmr.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtzmofcfih.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtexbhetbw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtqwklxiqm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtzztrpngx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjjwsbkf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtgmuxdrbj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtvwyrxmct.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtuxdlziet.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtbpoegixp.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtuoatduzm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gttmsxyuvh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtbkrlmhjk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtmkanyluv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtpuoitzyp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtihrlhapp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtfuqjlfqm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrvzlksw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtcvonmuaa.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtqdjrjxid.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtutpvduiw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtgthyednx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtskthgfaz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtznpytixb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtodydroat.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtcycrrdle.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtswouhhpe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtkesrvigk.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtacceaaid.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtzztlemmp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtzwixnqgs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiqxgefl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtpnbumbil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtvzkpoaxi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtaaalrmbn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtsuqglbic.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtcogsdlfa.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtybcisxwg.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gthjqtwmly.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtyqdcurka.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtzmexlnsy.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtunmigkkv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtnbtqhwse.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtvuznfbmt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtvurvhgfx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gthqcnbfls.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtsfevwdkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gttegaktsp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtiliqazfw.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtczniytpe.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtsqpvpphm.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtufhiphrb.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycestlak.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtipufxlmz.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtkudnfzbm.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtswbnupuh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtyoqurwzf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtnaglcjdk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtehdfbign.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtzjlbvpqo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtisvktwhq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtscpsfnjh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtvwxjnlwr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtorvvqski.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbfbqxrwa.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtoclkexmv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmvdzetxh.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtwoplbdzb.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gthhpkhhmu.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtjdezvqtx.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtlqyqmlxc.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtoxumhpxn.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtzyfacysh.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtpgyakkyu.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtnrvbmxax.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtrahezgft.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtsgldkzvh.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtwpugjacx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxlgessbv.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtlcpcskwb.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtfspkhjqj.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtmzysysjg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtqwzabsrx.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtyejnlcgk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtovzfjrty.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtaquozxxl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtyzamgzey.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtjsijkyzn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtpyoqalhd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtlmuzdcqx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtcedypsub.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtvvyhcoqa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gttyzabbsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtzbcscwjo.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtlneiaffe.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtvhvfmhwu.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtsngrernt.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtvvcbueca.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtvurhrdoh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtmbbsuaef.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtzshvjyzo.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtududiwpd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtkhxqyquf.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gthpurocnj.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtztivqxyh.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtfpmlnrfc.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtmeerdrzj.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtzlfaqwdj.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtorufnmbb.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtmvvcjjfq.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtbjhalkpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtgdxsvnjo.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtymktkrmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtohwnfgmv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gtjhhomniz.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtszsvsrkm.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtrpfhtfti.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtbwgonwls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtlwaibslz.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtgdapebdx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gthvmuqshz.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtfhnfpwee.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtgnkrowfo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtiaysmppa.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtczsuibfa.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtkjduusib.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gtmwfmdycz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gttoubmhmk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtfsthfjom.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtwfwqjjdh.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtmnslnmdv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfszbjosv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtvmxkskpp.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtspcuvkxy.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtmpleiyqr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtluzzescx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtkbcezwbf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtdvrohlxp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtjtizfstz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfoyjwzhl.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtwqcqumgh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlaoslfge.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gtgrlglrto.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtuewsdwxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtyhcgbmvn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtqrbaebxs.html


<!-- 参考信息 -->