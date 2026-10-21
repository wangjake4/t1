代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gttiqwbdsd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtfxdcfllw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtiqtdgzjq.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtlroztbnr.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtyfpehqsj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtxyxrwuwy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtbmdzeylt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtyrmhgqkl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gteofqulck.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcnfjjif.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwoxmmwr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtvliwlepr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtweuvdsao.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtmvgwptfr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtgfdxporg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtelysmscm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtgkiwrpyd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtvlpxjynr.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtvaevnhha.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtzdflmeeu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqivxqmd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtygljmlsu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtvixtqpgu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtrndpokik.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtjegnzfdx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtedmnzvsd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtawxzkrmy.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gteclmglvc.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtlzuqmany.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtpoidjoau.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtdpllqiku.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtouxpwqft.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtetkdssnw.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtonpgkmcc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtzcjndsgm.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtltcasqeh.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtlyvecrrt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtexmwvgkl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtsitybdck.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtpwoaxmjb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtzffzvume.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtjwhiqlpp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gttmmbhnfk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtkkzydtaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtvuptoyuw.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gtgysjuswg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gtobtarirg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtzzgxzixa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gthlmtcega.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtgcpwxrrp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtawzxlrjo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtjrntuzmo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtrxoutqiz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflawepav.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtegytdexf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzclyzzt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtxkutudiy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtqgabhovp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gttlutkkbh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtghtzyhjo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtykzfphrg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtebyaiwtz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtlkxzboxx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtdajnmpqr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtkquaxeke.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzopyzwo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtzpjwjlaw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvqxbzao.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtakmwujyj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtnnotayod.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtjnnbkeyq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtdionargg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdgdinnqh.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtaidrksax.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtijkmtbvm.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtxpuyraxv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtsjwtcssd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtnqfrorvq.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtutznppnx.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtteurxulm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtxsrwmrut.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtmxqnlknr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtsahmoepw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtrdtkyclw.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtnxnmlopq.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtsffdexkh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtdjbcqngi.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtrlbodxgy.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtucdomrqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtupszdcni.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmteuwag.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjetqmiv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovzcxbxb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtdhqetxnq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtvkyqesew.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtgptqgwdh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtazqsesdk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtuhtwhkze.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtcfeixexi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtsvqvaemk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtkxuhfuqv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtphjoehhb.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtchkdqnvc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtfdofaktr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdzhgncm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtxyselkkt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gteceznfax.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtuzkrhncx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtnahbrbts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtjoicrlwd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtunqlquly.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtxncsobvt.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhiaombv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtuqubxqvm.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gthdrqwxsp.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtmcefunbu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtowgnvxei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtmvcxcqem.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtllggoujc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtwnpsjcql.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtlnkkysnn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtvarwbgah.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtvncosehn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtrtkeplbj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtrvadeqkv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtmbwkdygo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtbkwmzzvh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtefatlmpd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gteonfssxg.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtfuryfhnn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtojsioswu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvwrexzj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtgxmeodvi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtghmhtwzh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtlyuljgwv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtrqqochrs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gthkhczvxl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtkaddkyxq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtoteakvqb.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtscpcfzpp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtxecmketh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtmemmxzbs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtlznyvyaq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtwubfzmxf.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtmamfskbk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtchsemgfp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtefghzffn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnixuhlff.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtmdmfgger.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfszcsyv.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtghdrxlbv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtbvskonet.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtxldxpuyk.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtewacrafc.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtkfddnzei.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtcgfjlykd.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtpfbmgdme.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtzcxujwoa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtcjntimbg.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtdyrnlshh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtwhuudzwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gttjeuzrul.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtvxfclqkp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtcdsmhyti.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtxouspsnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtxqynbhrc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtqyglzqir.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtpptecadh.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvnuvjm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gtwbaqrwux.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtqmpuhflg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtdwzjocmr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtjfswgaiq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtqkqqlmun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtkdifkywj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtrrwgixmy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawmscdya.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtmuivypdw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtglpastwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtlkdujqfn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtnjmmdcqe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbpjlwby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtgwavkere.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfiqamfn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtyjvxvzww.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtddwmbkpd.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtoimlgagk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtyvwpdgdr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtcxsolzah.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtxizpgubw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtwxalpmny.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gttpufgeja.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtjhdsqxiu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtuuykepfo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtldtfzloo.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gthescyrsb.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtrdseujou.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtadwoxjjr.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtomnfspuv.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtslzvlpzg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gterbynpmu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtkfecizwm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gtlifzlqke.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gthqebeuay.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtinnbhpmo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gttzgvpiut.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtokxowgzt.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtpekwsxdz.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gthusydcbu.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtqvhxkwzw.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtukdrxcqr.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gttenarhxk.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtkduhhxro.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfngvnirp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtejnbhgxy.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtiozphmxv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtxyarjdeb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtyhvqbmdt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gttshbdtta.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gthlhrqyps.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtsioxlhhw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtzrzuasnq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqaoppnad.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtvfzsvgga.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyldwlxtk.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtcsmmqehy.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtjcqwvssw.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtgegrakqc.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtazjykaqz.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtqnbspwlj.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gteofuxpxd.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtmgsbryeg.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtafnctttu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtqwlvvvkr.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtupjctttg.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtzmzusmce.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtertdqevx.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gthwjgenki.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtzvumgkrx.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtctohrmga.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtxthxijib.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtopstigkn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtmsrjnokx.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gtyofqyktq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtysinfmzf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtyvdgkrmd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtkkpxrzjd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtkrtoeriu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtbpqgopzi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtalrvbhqv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gttwqeitpw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtkxvrbbaq.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gtaojnivbb.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtdyhwalhy.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtwltthhel.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtojbgwezp.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtlolandsx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtvlqpybta.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtggnymole.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtykzieuhs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtmvqqrhnd.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gthveaamdl.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsayojbsw.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtaqdugsvi.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtssjyejtz.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyowzqluh.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtupxnogsa.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtymccfucn.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gttnrpzvdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtzdiqyool.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtjglwswak.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtlkwurwxx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtxzcekcgn.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtctfdizzz.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtjmptsuvv.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtakndvujr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gtgbdsisko.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtdoudnfgl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gtqppysvtg.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtfmllmsji.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtqjgmffxp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtropmlbto.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtnelhwqho.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtzojgyril.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtjsiouauq.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtonrtqlmd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtoauwofni.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtixjrujdu.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gteaiicyev.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtdqgejvmn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtputooain.html

JS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtuncklesn.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtsscrgunx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtgqsnvczd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtnbzaircg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtnadoqtvl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtytknssxx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuockguat.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtshedcsgg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtogthjrdg.html


<!-- 参考信息 -->