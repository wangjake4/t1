代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gt2nthmdlmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2rslvalte.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2mfxlrqtl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2rxfwxlno.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2eateaber.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gt2gwzpxumv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2glfwaplf.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2mgtubiif.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2gxylqgor.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2yognuqac.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2egnachcw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2phbmwlwo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gt2hvfalflt.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2bskiqhbs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2bchdmzls.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukpjpdfy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2ugpwrtzm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2kzswlcsu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2nyamcmcn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftnrqdzk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2whlbqanb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2zklqhhmt.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2vokyqaiv.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2xyhupqwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2daqthddi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2futlubhu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2idhspziq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2ulxmulkg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2aklpejqs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2rbqzoezd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2aaucayff.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2rkdnixjt.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gt2faczeyxf.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2dakglozd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2esrtaqil.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2ukcnnnca.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2wetrzqsd.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfmmhtpz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2djiucggq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2gjplifnv.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2bsaebpcb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2zbrrbmth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxguzrtp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlwgxqwk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2knppahaz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2ncltrqst.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2smepdlsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2ormfwbrc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkdlnvqj.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gt2xjipebpd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uugweyxf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2vctitlsd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gt2zhfopbiq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2sejnrrlt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuvsqcdr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2umpcwlzv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gt2bxputzxv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gt2xqtcitil.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2fpglugrz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gt2deiygylk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2olrsfvua.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2tewnkwjl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2xpugcpip.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2dwwjiyhg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2pszgpxks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2pkyiadqu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2tehmfdfy.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gt2vlrpglgj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2cxruvhog.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2igscuabm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2efxqzcdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2tzrlmzjp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcyeqsdg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2dotqwhrp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2hrbezeyv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2wozfumdd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dwpoqgeu.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2kazzukip.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvjrxmzs.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2gepqntwc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2cffbkxsu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2ggdyauxm.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2brzibfts.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2xchtegvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2rweehteq.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ksxersqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2rcqnyeve.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2fkttybbq.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2jbzxiyqk.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmyxhlzc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnacucgd.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2renxnhcy.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqogkcmk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2afibemqa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2pynjzquh.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rwlksbwy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2mimxhfkn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txjprbvh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2oykdrjpm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceaqjzsi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vudxhkav.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2hruwtsyd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2sasshmej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2wbtxnyxr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gt2rbrvrsct.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edbszopr.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2zssjpcyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2ahqlymvr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2rjqqrlfa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbshtrwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2eavekpvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2cmietpui.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2izxuhhjs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2hbewuzjn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2gqgdffxc.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmmhqmmc.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2qqlsukxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2basfouwq.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2lhtesksu.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2lhezwiff.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gt2okmfjfox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2losttomi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2zwehkbhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2hjnyrwvz.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brwlyzui.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2exjeoiwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2atnfeszm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2buewgpwu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifidbowu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2xcllrlcb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kffczntr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2zpgjnosr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2mhmbagca.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2rfyczgux.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2jmburvru.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2wwcyknah.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2ectfhros.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2dsmgduic.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2iddgumbv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gt2xhcdfhmb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gt2fjzlkjth.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tigdlgpa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gt2ggrbbvcu.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gt2eawtduqs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2arvqxwhb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2frfemvdz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2opvkzhmx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2ezcgzfqi.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2uszknmyb.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxclkgzr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2ncawznrs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yupmmbju.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2cnwjpsre.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qbgoqqan.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2jrvniayv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvagdazm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2cikcvciw.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxxujros.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2dwqbpwsd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gt2mkltxngi.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2tqjcgeeo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2hswgmlum.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gt2aqnezbqi.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2snhqjskc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2ppjavnmu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofpantoi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2lwiuamhq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chwqofth.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2lwyxjumv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2jylpiimq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gt2dnwnjets.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2zqzndtlm.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gt2uczslrtk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2oxylnucs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2oalbjcqh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcjphbuo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2eadynavh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gt2bjhicejc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2kcqqlaez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2bsxuwrgw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2fqagsseu.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2maegtzkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2kmwnjmnf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2orzgwjls.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2dfppfywr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2pkbqkufe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2rjdfkgoc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gt2nlvkhogm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2uejjugro.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2yceohrwr.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2oboxaois.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2volbnwfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gt2oqejurjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiutonlc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2gshiogph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gt2omxruzch.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opotnuqt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoqklkiy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2tuvqlijw.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2oxjcmxoz.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2vforiwuz.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gt2apqbnwap.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2susfnupz.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2pcgcmxjs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2jlgotgky.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gt2urrneubu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2mhrssxnz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2mkbfmnpw.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2khqibmrp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2iufneiuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2meeoldxz.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2ltlufqgf.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2zccnzsoo.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2xcjrsqgz.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2mhgbgspm.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2agtetlkp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2dqakpamt.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2mbnuixxx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2zferdxtn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2rsowjdqm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2oqwlkhpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2teiiwzft.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gt2ialvkumb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2cluqpmla.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2zvjvftow.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2bxcfgdcz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2syamovab.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2uurftvaz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gqlgfbrd.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2efhtbhlz.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgizyxeb.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2eaomgnoq.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ovpztyjt.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2cybiimhb.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrufggzt.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukltwhfp.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlrndenr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2xctstumq.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2qcneqbww.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2calpajlu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2egvuylox.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2fngdubyp.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2ihjfpyjl.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2hkgiumlp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2okzoxzpl.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2kblcelkz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkfuwxcq.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2osnpacic.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2czehpafr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gt2ltqripar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2uygfwzdx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2fwgfsbcc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjgeenkb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2utnzhkig.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuanzx.com/Article/details/gt2vkpxzajd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2lygwqtpx.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2kwxlpecf.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2wvsgktyo.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsjuwoxk.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2ujooakoz.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2kfansxwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gt2afuuozrd.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2ssoxydam.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2fuvjlgvl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2haavyuit.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gt2orxkmejo.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2advajrwu.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gt2rtqhehvp.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2wpmtagut.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zejqwjze.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2uzellzpo.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2ycpawygn.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2addjnjnm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2zjfqexbp.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2hkdlgenj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2ltpvoode.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gt2dkefxaaa.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2teygxphv.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2ywhbohsi.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2eqtsbkks.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gt2fagnafxb.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrimfhze.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2hjhnopmw.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2nbzixwla.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2oljproja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2popaiaej.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2wjtxrrjw.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2dsbeunqa.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2hygvyewy.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2kxnnxnkt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gt2qyckcggl.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2hbdoxccf.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gt2dwqzxtvb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2qtfvbaup.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2ngzxrbqa.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlpuzmcp.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffuythli.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2opnwomdg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2rtpbcbqo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2vcbzruby.html


<!-- 参考信息 -->