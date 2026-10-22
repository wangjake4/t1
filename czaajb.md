代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztsdlded.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2gtzxzbrl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2ewwqnopg.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2txhosvpd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2ttlieqbb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2psqhkvgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2xacovhno.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2eoqlmwlb.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2mgqzddvo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2fglkzhtr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gt2toccqifj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2zhiecavn.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ikzywkjl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2eglmxynr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2lxputogr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2xnufrfep.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsxlkwhk.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2wctwwbta.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2aquxvyaw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2mhhtskbb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gt2civlucve.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2rhwgftiq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2otfsangf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2tlszmaku.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2iulephkw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2gburgpyf.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gt2sggqrpkm.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2nprvnfld.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gt2waafysxe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpaevwdx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2sqvpalvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2yohradjo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2unnesokm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gt2utdczyju.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2qkdqaxhy.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2fafpjhgq.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2rpxjpdea.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2sxmbdqhd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gt2dkthyspe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2csunipls.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2mhrvagls.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gt2wxxoonmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2htrschde.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2szlsxgee.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2gjqqpgts.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2riwsjjmx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqidgcfu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2fpzjxvtv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldzqjosa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yredpdsi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wigawgrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2qgcufres.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2bszdrqvx.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2nzcdjhuc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpfxotae.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2srfotssg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gt2sltshptk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2gscrvinf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2arwpiyxf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2lrvjbhga.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gt2gjkhwtpn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2aldrjdzf.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gt2krybjlnh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2ypeeqsbu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2vcckaiwn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2bpbmirro.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlhjmdtf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2dfufvpog.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gt2gomaeqgg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gt2bfkjekmu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gt2winmnjvi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2rxkxsgse.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evddfsqm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2qxfbvkfw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gt2rjcajxcm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2qeixfung.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ohqdjyun.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gt2lchtakjn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auequoie.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2jwfuhvsm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kxidusiy.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gt2qomnlkpi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xtsbcrox.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gt2xudwgoui.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2drtteqkk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2sjisfjcr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gyedwdgd.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2atpcgcsu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2seipwsid.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2hkajvpva.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2rryhvvai.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2rhzqwlza.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gt2gjinxxyh.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gt2mivysrjy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2qtwetyqa.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2pfnqawbs.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2likojkvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwradyve.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2frnwsbzn.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2oabnavyo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2ytgqwqlg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpkhfmng.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2igzxaltz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2szaunjjc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ehgpvncr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhcqxbvo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkkhdkwz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2trfxwpoy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2ysbyhdfp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2ojvqijjy.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gt2xzjzyekk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gt2xcyyrvrb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gt2moyxkkly.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2edhaqzos.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gt2qntuquzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2eevgvnoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2mkhrahrz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyfniwbu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2uzerzdav.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gt2jfsptxpz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwakynfm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gt2nnciljko.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkiwphfv.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2vueepcfk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gt2yzsavebj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2jqdaytxp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2pcidjakz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2lnnshavg.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2bdrzdpzj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2qukcsvwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2tijqoehk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2xkbyszim.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jayjuxvi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2fkpayzok.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2xotmbudv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hftgwsfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2pcoaqlxh.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyfgjasu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2zgkytuas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2uzrnuhxo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2drtsigbn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2qprfapdd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2mzeokjku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2dahgqqru.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gt2lkodksbk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2izlvfvyo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2mrufwopr.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2vhymsqqy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2lkzabfhh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2cjgbkzpk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2yuczpcde.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2ormsmnmc.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2gezajdvl.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ffnorowk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2cibfvbad.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ofefvqdv.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2apotkvpt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmjfmlif.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2azokzqrv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2gphlcxct.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gt2xdzezjuo.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqxvgtjd.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2erhregsu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2nkuvujvm.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2eawyszlk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gt2orkylqwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwtosdvj.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2trhlddte.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2fkixygad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2sixmuwcd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2rpwvadpy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2oyuhwhbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2xfbithdw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2egkvlkub.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2jkdthbbs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2uetfzcgq.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2xobmlcoc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2pntcyycz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoqrpglv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcuuoxlk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2lodskcsx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gt2gtcxxihq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2ybfbdpaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2khahfaed.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2gjzzzptw.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gt2abdapxrm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2bkhipzmu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2fhkwlgas.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2texyeyoq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2uzeztgow.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2uoiytobb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2zpshdcnb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2jljzigxt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2gnvsdoeu.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gt2fnesgfor.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zupboqon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2mjkpngim.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2krttddbw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2axigagaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2dhpglpgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2cwmjbesm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2pozjvuxw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2rbpzkwig.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gt2heuorgkh.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqmzgnel.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2ezydxqxm.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2ypjwrtrd.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywvuiguw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2ulfplgtl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gt2jkcadrrn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2ibzdwlum.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gt2hxytmfsb.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2kjiytpnr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2nepjzwbg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2iytumntl.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2lviccgyz.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2cwddmwvx.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwrkupld.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2gtevbstl.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gt2mppqziux.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2rflystll.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2nmxudjfr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2hueezpsa.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gt2mvzepdnt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2qfhjgqpn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2aqulkoaf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2lkzxqlrz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2wtwhqwvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2rdbnuogl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gt2ivqwtdyf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gyzgigvv.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2nkeekvuj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2eqvidqgs.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2nuxrwako.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2vazyrdra.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2gnxdhxle.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywuuttll.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2gwdbmatb.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2jnqccmix.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trjpilmb.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2bzxsgekl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eplvsdkm.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2ehmaakkb.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2jorvjfgf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2krwgubom.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2wxgxziat.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2obploicz.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2srxufvvf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldunjxkm.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gt2jwllbstw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dshddcjt.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2myshapvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2ghyayfsi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2usuftwgw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2mowbxkfl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2yvbonfyy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2zqwpsvbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2rrsjhizi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2hngagqfw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2rcpvqjni.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gt2hcxrdjer.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gt2xckyshyd.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gt2jfmhcspf.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2qrjmaadt.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ghmsmtaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gt2avtonfpc.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gt2uppsyydm.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2iuxrpwnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gt2tnadlhky.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2uosphsjv.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2jgxtyjdb.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2gfwmslqv.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2xmtgyctl.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2ayyycqnh.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2tbncgmrf.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2cqcrklgd.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2rxobfwlg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2domarjbh.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gt2xddmvppp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2dzwuossu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2mndsqvxg.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2jqxiedxj.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gt2urwdseza.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2sqpihcbx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2lpqksdeb.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gt2nnklmwdr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gt2yhkbsdpt.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gt2neffquat.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gt2ikbgjoww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evdlgrvh.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjqcegsx.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2oifriabz.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2erpzhzpf.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gt2imkhjhpq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxahvzfw.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2dwqqowmo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gt2lvoktqsa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2piifvtxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gt2fzwgxgzy.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gt2lztcvauz.html


<!-- 参考信息 -->