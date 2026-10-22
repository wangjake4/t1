代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gt2zpdgjciu.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iphjkejk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2wdtpqwcu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gt2xxkvgstl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2rtluxsgn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2pieherlb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gt2yecdluaw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gt2lcbazvye.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2zpapylku.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldxvzdty.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aupwrpet.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2kunndntb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2sgdcrdyl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2zdaqrwlo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2vheuhemd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2mqzfxjvy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzipixfw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2mhfvsyut.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2npiogztd.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2msugqpzr.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2iicvfxha.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcjziqyl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npokyeoz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2sqnpbhby.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gt2htlwptex.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gt2fhhsdgpl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gt2iaovmxpt.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gt2htiodlah.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2jwpjvajz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2irznkmem.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2cgsqojco.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2qvkvbeej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2rrntcxuu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2bxybchxt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2cehwmoho.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2cfaotsni.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2qjlhgnzb.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2cunannyi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gt2lkscqojs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gt2zjictsqt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2cufmotwg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2rkshcyql.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gt2iffvjwhf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2gzvocumi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gt2samwmumq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gt2nkgcnupm.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2xnxbtjyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2ybdxvcmi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gt2iilnjmzd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2fkwzhaiw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2ihlogdkj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2apmefjbg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2qutcycbu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2ooeabuhp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2pmfdlbdi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2vaedwpnp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2yimldofo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2njgaqcva.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2cbqeuzqi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2blejyqoe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2njcpnlwc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2fdfdzprx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2fyvbdsbo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2zzxedkvz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bhpqhzpt.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gt2vvjvzotm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2bctyonij.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wdwooanx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2jlhcezwz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ngnuczvw.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2hiwbgupr.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqfhosry.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2glmsecis.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2lrcmhvcj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gt2wjlsgluf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2ivjrzhau.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2ycfuqrof.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gt2flgeoxky.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2znihejiq.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ocoyttji.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2oobentwo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2pjdngtbq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcanuslh.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2xulfbohc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xfnqvufl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2stxcnfqt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2svzaxsbj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2nnudekfl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebvmuymt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2mlmxwhwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gt2drqcyhcm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2uujaztcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjypendf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2fozxglbp.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2nmcuehsj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2gfdilwgu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2zvztggcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2jjqxaizj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2dkygpsvm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2dmdflbln.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2nlwxpxzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2ymdlixbq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gt2littqhgj.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2yoariziw.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2dmvzsvsf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2kssththr.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ebgmaine.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2cesreohx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2gvivlrot.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttgnmxmq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2tmqbhysr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2xllqyobd.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgrxpvan.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2mqfpbevb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2iyzzyvpa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2wkyzxiig.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2muxkaafl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2anmzuwge.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2lcqwhzig.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2tvhaaysi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2mnesgfng.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldmzxdxm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2dggrsjsk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2grbmsrcm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2ekxetkds.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2amocktaf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2pdlglask.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2palamkbt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2zpfcnaki.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2hdbtcokv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxdzpgy.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gt2nkxbzxsc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2dzfdrkgo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2yptrzoov.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2jcjkmogl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2zghsftoj.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2bakzxifz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2vnviyyxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2xyomvbij.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2scubvpqf.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gt2ojljzuim.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ytppzlii.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2hcufjtqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2sbmugynn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2krmadnpc.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2xmumukjg.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2curlxanl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdypxvw.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2ovosubgp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gt2cabcylbh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2yyotuqew.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2piuzyqjc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2roovdzmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2tpcarhue.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2rojmiipc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2kesfgqhm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2xttyfcfk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gt2iaiwvzpx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gt2ghjksamv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2owmqaltc.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gt2vwrjvtql.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gt2ntejotdo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2gvsnjczy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2sqpghdsr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2yansiads.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2htxyzkfz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2xjlkphvf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2cwfaaifr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2lcvtsbvb.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2givvrtxv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gt2satkkuyl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2kurfzfit.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2pgdersfm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2lubxuymt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2yqswruix.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vezcvfkg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2ouxcxrvv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gt2otokdpdy.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yktdnqtz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2tlenyjgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gt2jxlegetz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2jtmhnvzl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2mkfkyswe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2myxtwqwe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qqrdhqtf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2zjryadwz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ixyeaavc.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2tuboggug.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fivymhqn.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2gqquezib.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2nfpeembc.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2qzrhqymx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mctbxtpn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gt2nlxqlxii.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2exkdybew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2tdoowqfv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2crgaiowk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gt2kfkvtubn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2avpaoixo.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2muuqluqi.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2girtwbto.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gt2bmnzmovd.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2bwkktyar.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2wzawjxhw.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2deblkamw.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2jpcropfx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gt2odmkicjl.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2qsjgmyku.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2axxivexk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2hrcwsppg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gt2qloukfor.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2pzvsqpuk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2zldoxihi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2tzmgjehz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2xpaabnei.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2hpmtkaft.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dhlljhrv.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2givejksu.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2yegvowuv.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkciohpe.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2zkenimrx.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2ghagtugv.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2micnoyuy.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2umvesvav.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gt2ccelnkrf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gt2jjfmbnqh.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2ljweyjgn.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2sdpawdsx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2sgcjivlr.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2nomvpavv.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2hafameey.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2vzxjpnpt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2nbjwlyuv.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gt2rqfmucrb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2oxleiqwk.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gt2mekbgxxt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gt2pmydaval.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gt2kyvfdwhe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2cseflyuq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wklttsdv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gt2cfgsznjt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2jcilunso.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gt2xrzstnqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clpfujda.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oblubqae.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2waccilod.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gt2fveaobhl.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2uygfbonp.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2aauvmaxj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2gzgvddze.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gt2zcxpbzjp.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gt2vmoedcyw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2ueolcfgw.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2antgdtlt.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wmycqtuu.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2tzugpiym.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2yhekfzgx.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2guplmodw.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2momljqbr.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2cxhrjgho.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2acbgimwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2ijowccfl.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2bcisfidv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2nfbpbfyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2qoclscxd.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gt2mirwrjkc.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvounjip.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gt2yakrzwzl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gt2smxtfnuf.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gt2gcvaumyc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwlrzyun.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gt2wkwazpmi.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gt2yrigomfq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwszbmhp.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2wqactpux.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2vpewsocy.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gt2xlhkufae.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrmsapdz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2hyewpinb.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2eonmpstf.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2jixcneyg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvurkixc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2tqcgkpll.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdtpqecb.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2zkbayptn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2rrtlmnpt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kztwltfq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2qrelryus.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2qrpeypkg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ovdurcwe.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2xmjzbeki.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2borupmed.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gt2ukxtgxmc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2iwqevrzd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncdfaxso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2etyvmezu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2kzcxhbep.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2wxpayeei.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2yxqabwnq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gt2qjzxjugj.html


<!-- 参考信息 -->