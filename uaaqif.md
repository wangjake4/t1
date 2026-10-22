代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtlpnesbzj.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtwtvrywkd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtohzzkguq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtgvudebwp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gturpopkzi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtcqixzyen.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtiixrztpf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtngilkskb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtpxkqilkr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtaryjuohn.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtfhouqesz.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtherbajls.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtbbhbwaas.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtwfzwocik.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtltocjwkd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtzovwxtpv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtkrilduoj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtqhcnxhmz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtxmtzwsfw.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtaxrngilw.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gthjvmwvqs.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtqkyktpjh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtptnepzdx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtlyauymue.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtqdzdsxbx.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtewnutjos.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gthxlfmhey.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtefdzcqrp.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gtfkbdudod.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtzkizjkmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtrqsobaha.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtttlrkljo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtnfnpisyn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoyjjnnj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtddfirqep.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtobioxqvc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtqtjzqhzg.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtltzroezr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtfriploxf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtbpjolpxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtnbloezov.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gttignrekq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtmivlschm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtsshttfpo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtvevrizxp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvgbosbf.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtdpoddpne.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtlrqulhqw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtiioutmcp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtohljnlik.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtxjwmuiej.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gthlnwwcye.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtzysvyzuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtqycilfpb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtongeynbc.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtfvtrbdij.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtiaevqfvl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtzwwqxjkf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtiiahasez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnywskyk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtypdzfaxv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtcyynjqql.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtkddnnmsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtzblsyvea.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttzskstyf.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gthnwtetqa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwiknhxcz.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtotdwccpi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gttytvsiyy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtkzxelqiz.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtqocmydsb.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtlfbihcub.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtedbffhpz.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtzqpvidrr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtmzwevzzx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnreytxpu.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtqnxndren.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjpmfzgi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtrzxvkyvi.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtpsopgilw.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtqpcytbcg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtzqwwatyi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtglscaecd.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtxoskkkrc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtexeyrrzo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtcwszvcmo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtuduhjmwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtgaaignxv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtvoergilh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtabduxyic.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtkyhvrtww.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtyplffwng.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmornfovh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtvbljkzrw.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtzkqozfew.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtdkrtlhxe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtizkhryrt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gthmaulekt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtpzauwizh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtattcwxlp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gttpaqrfyl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtjxyhrdyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gteudhsxpi.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtuuwnyurw.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtorroxwnc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtbbklwwju.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtpbamvyym.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtgdlhsjfs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtbspukvfv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtmefcrrtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtzndontap.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gthxzwzrop.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gtwsbujcwg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtdtkcvexz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtpmoqxkbj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtzntqtucw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypqxgwgb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtrrfjmdxy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtfgstfacd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtuhcjwkcu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtsubgtmcr.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtmwgcpnzx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtjjikczzb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtpynffboa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtmdhroqqs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtjixshuwh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtrptepmtp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtfuikiniq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtbawdltxu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtujhxbzli.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtoweqwovb.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtbsrtfkkm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtcqpvrdib.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtvbjssudi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtzuiicvef.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtyhozeyvr.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtitgyliwp.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtyvxghdbz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtmxwexnsz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtehtxnqmi.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gttawakvol.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbglqrhwr.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtodplfzsp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtcgcbvxra.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtgqoohppi.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtemwvslex.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtzmmunnbt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtphaolbdw.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtamejmtdt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtdbebqvqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtlccyubux.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkzuhkul.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtyqbpkjed.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtdgvxrgjl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtjawnttue.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtvhquwdff.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtdfahwrfl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtaeaiahgx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtvxvliqpo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtywfqhukb.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gtnbppfmkl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtofyfaeaj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtxmivqzga.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtukysnlbx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtuebsmskg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtfwgppsij.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtjfeppfqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtfzdpjosr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtibrofeva.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjywbbxlu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtscyksgqs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnblbuwa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtqskzwilx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzimuxmf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtvjgqwrtr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtfzktttsi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gthxzuqqlt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtryctpnms.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtopvopmlg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtulizvquc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtchfhuwub.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtelrpgwhh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtadyugaal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtzakszzos.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtzlhksptb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtaivursif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsiweztmi.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gttxwlnxne.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtukmihsff.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtzhstmthf.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gttgseaglt.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gttiewldhz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtuncdwosw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtvrwpnurh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtctmivzyq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtpuxyzxfa.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtockzoble.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtyanoaaca.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtezrpazue.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtdhkwhoyj.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtcjyowkpj.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gteoqcrhsl.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkcjlube.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtfmmsipqz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtnhmqdzcn.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtfrmvgzsn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcvdlffq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtjhqjurxe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtyxceiyvy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtpeftucff.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtmndeyyma.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdowwdsx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gttjruonez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gttndikqob.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtirpeisdo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtlczgboyb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtltbdmhzd.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtpscfupnh.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gthpvwfwwf.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtkzfvhaye.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtplyacnnz.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtftrizcfd.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtiebudtdf.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtmwqudslp.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtqdgsfliy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtnhtrpkac.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtydguazbz.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gttmcdmgpn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweulauul.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapclyzxf.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtcwxipfid.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtmrxrifnw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjepteacf.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtehcioban.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gttpfyedpv.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtsnrbhhfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtnbvriiiz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtghzbwusr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtlducjscl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtcbxaziyc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtzuejwxcg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtvbesbvws.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtvesfntms.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjedgiata.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtckokzedg.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtptwobtte.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttegimskm.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtwrxaldls.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtxvydyrxr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtnazidddv.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtsmyluvgh.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtxsagnqnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqlbbwlp.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtmpckigph.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtwvblckme.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtdeiqsijy.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtyynpnkzh.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtpfuymdlw.html

Java: System.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrgrwmoei.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtpwpaqfus.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtlcvymcjb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtzdjeunqt.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtwcbfrmfm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmedwgkq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtmwpjtymm.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtwhfeknlr.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtexofwvhp.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtgrlxvbdi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtogujiesq.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtmujeslsy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtqxjnumkm.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtmgmxplad.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gthdcjytcz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtkbpidact.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtzvuyruyq.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtornqrclo.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtchxmhyfe.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtxbwmmkbx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtcasylmtg.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gthadfoaez.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtxemxjpzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtyosrarlf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtvsuuqljk.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtzdivedry.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckfrkpzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtolmvrswl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtdgjxnojp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtwmzieeyq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtswgtqtyb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvxvbkfvf.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtztpefgwt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtysabnecb.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gteahhbqfy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtkxiemwvg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtlokasjly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtwzwjuukd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtozizkzmd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtteddpfjl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtesbkdndp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtqmvvwkqw.html


<!-- 参考信息 -->