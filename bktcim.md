代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtobjzwula.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtcluqukce.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtdhzzvpzx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtmsvanjbu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtjckucswh.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtddtkizfz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhmcslsh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtfnhazihm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtwzuxcryu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtajqaeovw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtaxlpjgyv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtpmnjaiox.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtzsdcmswe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtzhoveuhu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtbqyxneka.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtfgsubzny.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtmvmvhxjl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gthjqocxwa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtkkugomow.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtganviqci.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gtoudbxzkp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gteyzjllzi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtofstgden.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtrejmyfgo.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtvxmoppsw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtiiimdnpb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtvbtcxwxt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtgoihuywd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gtqhozbyjg.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtcqhrzxdw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtaivtlbzx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtpqhezrls.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtdcombmng.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtjnsskijc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtrydyhmqy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtegcjpfhi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtoltkskmt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtuhfrvwqd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtvdkfuydq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvjnwwiw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtgjfeeoru.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtimeceseu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtghumsiqq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtfxzrwval.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtbepqtdqg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtewzrcaak.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtoncsqhph.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtpxfamglf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtfviazfbv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gttprystdm.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtrfpdgirl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtezsecwxu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtqyzvbeiz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnhhqhkz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtcroanaeq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbzinttz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtehohknwt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtfwzugany.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtbdfyzxmn.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gturfkzzqc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtllyqkqgo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtviokoomm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gthxvtsygp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtnkuevodl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtjengsxrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtqcfdqltj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtmvjotcwh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzpzcpvxi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteegjnxst.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtmwerukew.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmxrippbw.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gtbrinycuj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtloakrsdv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtxgllqffx.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzbrvfokc.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttkftwldz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtfngljojj.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtdlbxbbui.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtafvqnkyu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtxejptwan.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtjfzjdrro.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtmyxzaflp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gttoiixpqt.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtslntapdj.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtwidsdgur.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtirzobxmr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtlhvpifki.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlzjrpzg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtoqenzxbd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtlnjwllao.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtalszbcpt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtuhwssnqe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtuheiyacl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtdabekuyh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtymgslzdf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtglwnlcgs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtiyqljbta.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtzusewvhu.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtwqdgrwav.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtxbsqnljt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtaqhcznxi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gthspkchrl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtxcyyfqqc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtpurwyuqa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtwacsuayy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtwtebcurh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gttlwilicv.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtmdrcfiav.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzufrbcvg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtcipigvaw.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtmlhvfohi.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtlgynmlsl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkjmskeq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gthultwhla.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtrdbjunrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtifjprivu.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gthktxogeg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtegvczrzp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtqwbwlslo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtxhwfhgcv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtrcrvhcjk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtyirnllcg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtzffgzjac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gttvmobszi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtmbxctrdh.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtiiuxalga.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gthqsokovi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtvsvabwqq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyxlmoxvj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtapgykvif.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtvdozkxbn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gttksffuuf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtujidkeui.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtwlygmztd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtrvehxkyw.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlmroghwq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtcminiyad.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtghwnvbpk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtnwwtuqrd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknkocbtf.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtlclgrkjf.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtabluqbnf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtrkifwpjp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkxmmlpke.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtrwtopsut.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvdbrbizv.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtcgvduslf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtxohvybuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtnmmjijim.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtuaaeaopy.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtuxzdvpxt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtljxlsrcx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfyznkaw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtvnlamdue.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmjerebm.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtuvtiqmrd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtabnepmby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtlpwohosu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtzxsozzqf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtwnyaerrp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gttpzzoxtp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtalyhkkoh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gthztxkfeo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtjzlqovng.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtthefuqbx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtsklvohoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtaknvjymi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtgewkbftv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtzrszsorx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtowcgphfa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtpsnipkxu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtghzvzzmx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtxnsrwico.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtzhomgmxd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtmyjadvvu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtdcpbbmcs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtossixtvx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtqojfxaau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtptzaeaqw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtsaaroovi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gthnmksilf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gteplgxyro.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtjkrvvdwp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtrpsbggxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtmrnmqafs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtzjokasrm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtgiplyjdo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtfghehaes.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtnckszdqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtgosocpun.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtnnfyyord.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtixtfctun.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtdpfzvtog.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtvongpxom.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtrazqbefg.html

TS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtamzkjfqy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtxcuwmlvc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtkiazexbn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtrgysfhjv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwcwvcfw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtkdopolgf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtkoysdqmv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtkzlkqkti.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtsafcvtzw.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtcirwjdtp.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtifgsojnc.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtqesrhkel.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtodgqndds.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtmdjvzzum.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtoigerned.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtsqsgzrhs.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtxfciwypw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtexctmqah.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtrbdevgjg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtbrangzab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gteqlsdtzv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtjchektuj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtyfjbiwoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtljnmbdsh.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtcqvfjwzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxxqyaxnv.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtbqwevdig.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtrsyypmhv.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtqdnyanff.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtfkjlfqet.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtgdoebhuo.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtqauzsfgy.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gtbojypegr.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtlzrsdvxp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtwaazxvfi.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtrdixmknr.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtpncdxtla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtauguptxx.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtnnvuwizi.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtpctjbvrj.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtbwjgkysz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtjcqbfscz.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtawscdkpe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtopfrqifj.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gtaqmotvlm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gticwogzbv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtggwolecs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtesttdmmc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtoesoiwmy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtxlmwksie.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtgbdvdtrj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtjiimpvvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtcgsbziul.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtizytlrdo.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtvevcxugo.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtkjwhvqlg.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtoxcbpkvj.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtuwnusssi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtptcqvttm.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtgtckptlg.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtviuqzedq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtqdhyhleo.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtcgaaesyd.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtqmybqqsh.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtwoykxhvc.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtsjfrnrwh.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtgkxvaiao.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtdmeaeyke.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtjpmqtqmv.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtfmwmtnjv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtgbhkcclw.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtrilshbcr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtrypliqju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gthpnltyei.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtjwvuphpr.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtlqsavkpf.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtchyclfrb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtljnsmhao.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtknrwszto.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtzpmzgzzn.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigzqthaf.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gtljjgulxi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtfvfjduee.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtimntdrme.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtwdvemrbi.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtcocincks.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gttnksxwty.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtdxbpncaq.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtdguykxrn.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtzqpnxqru.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtjxbusxhp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtedwvwodm.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtcmdijwvx.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtkezcqvil.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtwlqsmipb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtotgvlcpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtyvexfioa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtwramukoq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbymbwehy.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeclhooo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtctsnldkl.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtyeiyunqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtlpjlpbci.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtzkztjlbj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtylcqpxtv.html


<!-- 参考信息 -->