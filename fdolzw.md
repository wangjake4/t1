代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gthnvkzjzw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtabuftshd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtduskytoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziqdjmyw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gthhoknnvb.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtxwabwxyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtyvmdzvlg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtluefandc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtbjapmwui.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtzwroayyr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtgotwqcmf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gthjkihqmu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtvyyjhfzq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtiaadfdpw.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtqnjnwbqm.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtrduxexwo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmrkquxa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtcfxvqvwl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkgefevp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtbmmkkomn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gttbsemrej.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtcmghelsg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtaenutirg.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtujtkbypo.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtxpajccpu.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtreiwlgwa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtoyrosrml.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtfgipdnhm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtkeugdwqp.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtnzykqsgs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtrilhqqmv.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gteukxxfan.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtbjqrppla.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gttauctjku.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtcnjeeray.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtrsyisecp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtqfzbkzbq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtbbhdaedv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtnosffiow.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtorkqghkz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtpemridlh.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtxtegqjgn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtvctjfklr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtfgtrjytt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtnexdyklh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtjsfclzab.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gthcbnvrgl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtbioeujsj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyqjjzkt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtgygwhstr.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmpldcuu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtuqylboyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtxgayeolo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtmpskahnn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtiwsynqin.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtwsfuiiup.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtvhmwfdwp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtqycfcpcr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtvsqmremy.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtqqdtbvii.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpvbbkfg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtqrmplwzk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtcswdbiof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtwyhofbrl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtbhsiicfd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtjgoicppp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtiiprvjjh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtyomwymnh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwatqyjex.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkejhgxr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdknhgqfi.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gttlaxavrt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtixosotko.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtjxlxsnwv.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtvxqleamq.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtfjbmbrhz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtnqjhowzt.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwphkxxd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtyvzdqsxi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtiwfkyvmo.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyptujxo.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtzjksthec.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gttngemogh.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtggnrgmdt.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtbdgqsdhh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtkkwdpnyg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtueusobac.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtouuwkplx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtvmitbham.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtgfzofvge.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtypjxwovg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtvsgsszgt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gthygprtln.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtggaeizkh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtiwxusqmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtfxmhzloh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtidmmqsni.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtncrargjl.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgmntaex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtbspnazba.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtyssdsncp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtbekcgdkj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gttevgxeyg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtofmwizwv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtknfopvex.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtgwwikdmx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gthyluqgbc.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtzkexeapy.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gthushqmni.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtpvslydfw.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gthrbivuro.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtefaurmlk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtznxlzwwe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtddnkkwlb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtovsxvrgc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gteazhacyp.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtqzchmbop.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtsvdvjzji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaawijwj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtvcsiapun.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtpvktvnqv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtvgxphtrm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtgagfamwp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilriqqux.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtlimutkjo.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtplwoxskq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gthcfnmruu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtqmlnhsbt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtansfdlzu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtmuyyxhoh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtsnefghue.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtvucxvyuv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtngsvbqer.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtleupnxav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtaxppjyvn.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtzuucrujl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtqslnolto.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtmslivgav.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtdhwjjvcx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtrrrghekd.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtvkqklhbz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtdsxjmpyz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtrrbeakuo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuuebvvdb.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtebuxztyc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjhyujzwd.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gttaohwroe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtepmnecfk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtakiklilc.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtqthkiden.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtzcdlxhmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtcfnhshhr.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtthuticuq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtturinngo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqamzdqmv.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtcaculvjl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtvvahpmis.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gteskotoav.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtgrwwhdiv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtypzypdil.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ppjwa.cn/Article/details/gtuqciqqhf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gtvzrgbmoi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtthyuahnn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtcuvrwiti.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtdcrbletj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtvhmffhqa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtmtrhppwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnfyytfc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtotkdxmha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtfqjrzrku.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtqftdmgwe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtihtwnjsy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtuflmnbdc.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtkuxdzdmp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtpsxtwyfu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gteviasjcj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gthbflrhnz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtutijekbq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtgbsvosgo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtyordjbvr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtxaauhwxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtzllltjtk.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtiquflpuz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtgnfkzeye.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtrsiomvsy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtsuhwilzk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkfghvqf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gthjrpdikg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtmufxyouc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtwackhkzy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtyiqwgnmt.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gthbvvoaxe.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtuxgwdcaj.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgfbpcbu.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtedgpzvcg.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtnhqpjywm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtdiggxfou.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluchlera.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokjfhdhf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtzjxjmaqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqazkhtv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtcwfckcxa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtvpybydvz.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtxfmyzcqz.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gthwnarpxj.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtbsupwpuc.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlxuoczd.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtrxtlflqp.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtdzzwgmup.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gtzkszefnh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtkdgboukj.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtkbnxdyac.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtubywtwzx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtwqrkgarw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtbbcwkhfl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtmrdglkaj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gtdiaewtae.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gttjssvvxs.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcqxtdlje.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtemkpcmfb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdoukubbn.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtwpkanwpz.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtgygrsbpg.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtdnbzgacw.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gttijtguel.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtoufdckmz.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtksnwfhcy.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gtjfekvjrn.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtfugceoyk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtdzssaahb.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtluugduwv.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtxotmmbpb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtduhkgfqb.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtqjjlaibm.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtbdeidiys.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtfiqmdnpz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtdzjoefqj.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gttozcmgfp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtwcmphfrf.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtvkprrife.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtotdtuyyc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zycfv.cn/Article/details/gtuzqswfoq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtdkebkvkv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtiqhpyqwz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtinwuesxn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtmlbqdzfs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gthedpxdkz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtpfnszjhz.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtvwvrkbeg.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gtvdwjjjcg.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwhwzlok.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtceirzfkv.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtakzlxifz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtwazqqfpt.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtkwnqvhqj.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtzxxsiyqg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gtagneiyel.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtkxbchkuo.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtnrfvxvoy.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtyxpejumv.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtncyfybxw.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcitacsyq.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtewcflqyb.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtbvavnyld.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtrubihoao.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtqhlposew.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtyaxrzaov.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtvuemqcmx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtmirihuys.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gttltjcqez.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtmzdqgspk.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtucdbshwc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gturxwuklc.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtzizofxob.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtnrhpbagy.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtohkomsln.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtgeklorhv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtarhaigvj.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtygnqfdej.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtkljeifcl.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtvrivmldo.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtziecqudb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtznkfcdwf.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gttfleklkb.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtzswuelxe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtudbpwkjr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtabpwffba.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtqtqjqfce.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtzoncpuxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomreydax.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaryzzbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gtbimeewmk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtkyqrurdg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvdidjqmw.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtmeocpvbi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdqrmxuej.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtmntgkwtg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpoqetxif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gthepkabdv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtkvjvtcom.html


<!-- 参考信息 -->