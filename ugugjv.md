代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2wmctytgw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2jaycrzny.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2ruajdbaw.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2lszhagjo.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2phvcmipf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2btmeyetu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2oktxsmqh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2ovpvondc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gt2mxqzyppt.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gt2eaoahmdl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbxfzhrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gt2ztccmgrs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gt2ecsnnigj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2wfcqpamw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2bhmndohw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2wbweqabp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2yplagbco.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2lwegpogz.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2tmkxjmfx.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2agxxsdpg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2prluvfef.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2idcmrbnj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2dltlswgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2aluvuphw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2ohvcklcw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gt2ihwmysko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2hndcrwfy.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2oegcpdij.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2pmnprecu.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2whouiseq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2kpwjoqzc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2ghveawwf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gt2vrznvflp.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2swdaxwwi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gt2yqytzcrv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2esuhxupw.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gt2zxjycnsg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2mwpqirgl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gt2upbnbwgc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqbizazq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2gxyidfjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2bcpzuxog.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2pfzryaqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2kgvxbmph.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2gceackrv.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2zyzagalo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2fypynwfj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2snaucrvm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gt2yubbafkp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2jknglzfg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2tqqpiipe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gt2tkuiwwxu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2fhbzjwtu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2cjhfdsfl.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2bkxwvjbf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2aazwvndj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2zustkqtr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2vdkucsfo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tssffrvm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2okrcdaue.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2shrsvtcu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2dqntuplp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2vahmxorm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2dlngjayf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2tlhduddp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zheedglj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgnmszpv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2sevgphqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvxirsgv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzlaquw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gt2rfhezbxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2imcphqtv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2axuhcbsv.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdnsvcdn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kzdddejo.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hpfstctd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2xvhgfnlh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asekcexb.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2howxeehu.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2tmsncgyh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2gmigchdn.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpkjuqcg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2aefeuddn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2devfvhhe.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2vphtgwux.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2rwgzppsa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2evurming.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2dyqtxlgr.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmhiicwc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2ggvzrwrf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2efzlulyx.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2irkhusaw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lhpbpnuc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2fuhwoknp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2drcchtmw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2uwpzwzag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2dgtoffcl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2gvdibtuf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gt2qwotcuun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2orwhbfol.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkpthuzs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2ficmlsdo.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2oyafssku.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2dlizoavp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2blsqawsv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2mgqzsdwd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsjkijlt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2rgxhdgvo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2qzpavxjy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvpzzyxd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2palifivx.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2cxxxjsgb.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2dxwwoeed.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gt2wxpfggek.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mtrxfdib.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2wxavqytw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2zodppgvj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2djlikuki.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2fonropzj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlvicfkl.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryoorwpe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2wcdebkun.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2vbsskjes.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2znrtptpp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2wglkgrih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gt2kodrrvaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2jwifjewg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2evxksaxx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2zorzfgnu.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2mvxlvpue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2zfaikouw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2vcnrghms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2oioxvfsn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2eaoyshpv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2wirsjqrk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2fljytrqy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2jszkovgl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2ftrnbrst.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmcilulp.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2kldefumm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2ymajciqk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvzpolpi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2yijrkhru.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2jlsuoltc.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gt2duhrgwuw.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gt2oxxaslkg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2tairmzkp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2auhzpool.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2wxykultl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2opimtrxa.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gt2fphuewdl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gt2ohzuzsjg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2gmfszedz.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrpcdznj.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2mvjhvapa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2evqiuehh.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2rnrcealp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2rcawdvtr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2iqfnwwrm.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2uxsgthkh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2padypspe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2rbyamqma.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2yrlvqfsm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpiaqary.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2krjejndg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gt2bhvtzzfv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxxasmny.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2brvumrsq.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2cwldckrz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2bcunwref.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2bakltzti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2ymukifwe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2tylvdwhs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqmwtyox.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2hhdnbmjd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gt2rfknqyhy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2nqdzsazh.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gt2tcemlmqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gt2ugzvzird.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2iebcgrde.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2xgdwsjzj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2qiyfnixz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2efxgofhn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gt2isakgkvs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2puwesmjf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gt2czajkqdn.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2fwuttjfw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gt2phbjyhmk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gt2cewllpfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2thqnxuvq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bncrnfaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2zsrdcjpq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gt2pwlalfib.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2hhkeedvd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2xwkfassb.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnpgqiwf.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2ygcoisso.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gt2hrfjkrez.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2ilydspmr.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2ocraxhom.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ajgcodbi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gt2fcnwoohx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2arsmwjhn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2smwwukek.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2gazdjaur.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gt2rsbcncfx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2hulhkxgh.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2vrakcuto.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2iqwqrmet.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2kpbcabdk.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2jlupqfym.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gt2hinydkva.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2kebdjrla.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2yrksbreq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gt2otuwowda.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2oaayusvh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2egvkpzri.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2kslkaqes.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2bxfplbzj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2zptufemn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2inisdjci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2eanjlxqc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hxhyxxme.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gt2hpfsejyy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hohppojp.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gt2abtyqsvi.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2ypqrxxfk.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2ftdqqbxk.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuiqzhdd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwemeoiw.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2agetqong.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gt2itguzeyl.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gt2qhlarhgt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzmdcipb.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2marofhnt.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gt2hxzcgpwn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2fhuanmkb.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2pakhoeys.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2keelpovf.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2mdvxaoek.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2gwdsiqci.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gt2jdrkzkgz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2xlozadyj.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssnhyapj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2lnfpkdwq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gt2zbtkguhc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2oejcuvph.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2oneyftih.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2ygejhonm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gt2qxggmtoz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2vyfejqpe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2dvignmgl.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouhcclli.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wodiethq.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2vplsqarm.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2quctoosq.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2vmrlebvx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2ergtxtmq.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2ixifmxxa.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2irbukgri.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2pfmzoblr.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gt2bnndkkht.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2vpqxfhgi.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gt2wdksffef.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2wpokgelv.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpcmyaem.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxxeoodo.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gt2jvabndhk.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gt2fkonuugx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2ywatpkel.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2crciwptn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2ffbljeqo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2raxpramy.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpnykwmc.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2uhxopddb.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2ewgrilvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2wufrrvkl.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjxyjyrf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2jeikucoh.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2fpcmhqmi.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2hwafjebv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2gotrqkcy.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2mvjpgoce.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2laisefyf.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2yskvcazt.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2potyvzlu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gt2vmzzzzxu.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2slhbjmmo.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgnpxykn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gt2vyykxctw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gt2otutfjzs.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2dqkreqcw.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2egmhlbmp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2fcwhxthz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gt2bzzoiixe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gt2fpdprccr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gt2evyksdey.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ieqeucmn.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gt2cxcotcyj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2sutdypcr.html


<!-- 参考信息 -->