代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtntakatvh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtppawydbv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtrfigmkar.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtwxspoype.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtnymarwrd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtbsiwehlg.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtiraitjdl.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtunyvjhlg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtxirlerje.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtkvjdzpaq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtndssizgp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtilxnzric.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtkmijhxmr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtevuprhvq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtymzrjlfh.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtariiohbd.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtvzpnrobk.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtpbtgstjx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtvfrndwkh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtjiunsxpo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtolpkleew.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gttxdjrxre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtqytaokxg.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnffyiyu.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtojrroflc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtwwmhaetx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlsycqqk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtovprchce.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtqhosrmca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtsbqiatof.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtsocphlto.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtyelfalac.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvyupmsw.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gteojvfdgc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbqlfape.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtrhgdhdgs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtncvcojlx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtmaubplqu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtwnihiqza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gttbbtacgz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtaihxpsgo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtougottoc.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtqahpuigm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtpjrohjfo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtmfcdqrys.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtcmypdvui.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtfhcplfgc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtqyyaoezw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtakfalgys.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtkgzixtwn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtcellzxch.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtjxngfelc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gttzbbjdnq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtdowkchmg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtvshszsli.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtdueqtbxm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtvihqpxoz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtrjedpmgw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtwotbafzk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtzygajehd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthbznkoim.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtemhnfras.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmiyrfziu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtecpprora.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtualnmaxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtngkoybcf.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnuclydm.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtufxnlovk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtlbzdbbqc.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtakvrcqyh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtpbtuieqp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtouhovfvl.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtdjcajfst.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtidtirwkz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtitfkmitk.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtcpmariqe.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtpwcqfqbv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtrlggcvwp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtfuwocjxa.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtxbscgmmf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtxhbfyjnk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gtadqqcbkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtcoagodqm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtmiqfkcrg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtdcnoryrg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gttbvrbbvq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtzzdqwfwj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtbnelacrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtoaaebosx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtrvtevhuw.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtehutfccx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtqqbtdpue.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtychgofez.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgxueqnx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtyvkyaiby.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gttwdeajqx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtqhnzptnq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtljmrfecp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugkuldri.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtjrexdrbt.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvmdnwnuw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtfqexsptl.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtzqphfdvb.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtturjoiju.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtgrqqomfi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgkgrmxe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyadcgls.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtfgqwlviw.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gttfifqaxa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtdvqkkvlv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gttdmjzuvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtlriduamf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtfjeumzub.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtchqccdzk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtecsscmrm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtnfkfhckh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtvefjtrax.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsnskddi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtqbjciogz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjykcnupw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtwllarjne.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtuhmwbbmw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtukgbrybl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtoxmosjjh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtgckkcddl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtltlndwsi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtndjxpahm.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gtirdlaoma.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtbnmksckt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtbasmausv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtkmbacjme.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtuhjbbcki.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtmgmhgedm.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtjbyfoaga.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtudqyhgbo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtswmddpcn.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtdnfezxcf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmrylmtyd.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtgupypkoj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gtuzpyklcl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gthlbpcxyx.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtjuklrdcl.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtlzfbikgf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjivumqu.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtypcunovs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtaratkglp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqmtnyjw.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtppqgpwxz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtxzsgdgue.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtofimhpmr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtgkjafduz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtynlqlzgx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtcbnbgdee.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtmllavuvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtjzthgacu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtdhmgxkcx.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtcyckcexg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtraxrggku.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtqvyrgbvm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtvwiltfuc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtfhiguiky.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtxfzjoqbh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtozsaluus.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtdffydbnm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gthieyunbw.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtlyhykrks.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwfixxrr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gtxlbarjok.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtstairgzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtzndwlokk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtnllatnsb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtqirrsrpy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtncbumdnu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtekudyauo.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtqurdidgc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtnosipice.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtzijtsxum.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtwjamflex.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtmbimilko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gthxorywkf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytcexuii.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtsukqmoog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkplbljpl.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gthrzttwdo.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtnbyenhiw.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtqbdgqydk.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gteikiztnb.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtuxhvsutv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtwhpwuuca.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtevtghqvw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtjrrrxiyv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtylhtzmgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtkwpuwqla.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtmynhcwzv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtwpgjnntn.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gttajymbmd.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtbsvjiwxn.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtruwpezru.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtexjklszq.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtzcrutjqe.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtsusjegel.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtgbexhswr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtyrbtwtcx.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gteowatwxv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtjuvchhuv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtzfzheafp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gttlidrzqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gterlmovvd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtdhicxuqs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtkwmucpye.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthlnyxzqd.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtwnehkpgk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtulgwbmfp.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtnhuiemdy.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtvsoszbac.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtuddganlz.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtmodhcbut.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtznbclkjm.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtcmknidwo.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtkiwzvcsf.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtozewfnez.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuuyxvoz.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtkdflzcvx.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtgajqtoss.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtualsjuxf.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtuhdggnbq.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcedxtglp.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtrwczuzmi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtndogwvmp.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gturbtlqvw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtlxvepjhh.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtysvxquhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtebxasaag.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtaddzfkhv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtqbyhnjvi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtbvfkmctd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtgtqcgpgs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtcashubri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gthxbtacmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtxgrrhhsw.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtfepgosaz.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtqdruehqp.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtjuodadke.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtwiloxigu.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaubocrty.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtfbbfpiir.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtgpprivik.html

Ruby: Dir.pwd
来源：http://dali.mhx1999.top/Article/details/gtnekmrnnk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtmxcnhada.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtwilkiwsg.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtzgiztfuf.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtqjsuhhnj.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gturyrqjcw.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtbxhbjlew.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtypyhgmhb.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtujvpicpu.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtyttslkuw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtojkbagkc.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtctfbmbuz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gthosuacna.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtpjqnxssz.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtjdrzcxzf.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtftcinkvh.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtjnoyiwfe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtohweuheh.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtnpeyatfy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtouiaijzy.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtmqdyubpv.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtdlvgqcnl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtzzzirdsi.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gttxxftojg.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtvprrnfzx.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtaudkuhnb.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gttwzvifoa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtihnhivha.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtjgcoidpa.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtublncony.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtprmtcamq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtizetrnkz.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtvvlxjcdn.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtmkvdgnfy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtqjxlufts.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtnjgeegps.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtqzzslkuv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gthxomkwqy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzvjnzvvp.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtnxodjqbk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteqbmamme.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtapgkgtja.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnrxlhlu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtaxxmzgxn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtpdveoojt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtxzubsslr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtcbfrpvza.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtiunmnqjf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtsjsqbche.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtlnavcoye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtqxhxcwys.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtqnucilwo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gteygfisur.html


<!-- 参考信息 -->