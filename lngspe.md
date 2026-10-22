代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2ttguokzc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2lfittwbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2boegczoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2prwlwhrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2wcgihrid.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2jnpiripo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2allbgdgu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2drgbsmuj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2qkcchlae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2pjhdbcxj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2snnhgzkc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2vtsyvzuv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxfmxsow.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ovspngbw.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gt2gfyexbjy.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2ykdgzvnw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtvkjnhp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2mueerzac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gt2zmcikbtc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2rltdczfv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdipdoka.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gt2kxutiule.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2nxjmaobj.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2cczaqsbn.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2tfxqjuou.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2ovqqeqyj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2xpoiegcy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2hvdbpcvk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gt2vzbnslpa.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2qmwlonii.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2faufwdlq.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2ukqshdex.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2cnaiwkdm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2xfvdbydq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2mhwagisc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrkgfobb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2acsdexkq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhwrfzno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2mzuqpqem.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2fazwlthh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2xmckoyzf.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2ojlkjlne.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gt2aqdrrarz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2ujjciyde.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2umfltjtl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gt2mazgenap.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2gyajaflj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gt2xfmutwxu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2uympdyuj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gt2rqimvyrz.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gt2lvzwchul.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlpmldxc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2fqskmfrl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjsvtkaj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxolcnsf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2dccsuohv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbbtjqvd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gt2xyhospfc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzcawypr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2toinbtgb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gt2picqfgvf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2kcaccqvf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2euihifrj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2urtphtqw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ikstyimd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2iobvfyze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gt2amihwihq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqksqvqo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2vpirywmr.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2pdpgtsoz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vywbbfth.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2jxesobff.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2surexvti.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2wlhhheyd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdtbebfe.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2zbglylyz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2tamyukgw.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjpfmgvi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2tgkhcqen.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lojibbjk.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2rqelkarv.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gt2hvuwdhme.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpwzkznq.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2fxwlfoae.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fojpwhau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gt2iahhuxic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvbgdcpc.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2qbrqxnpy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2xgoaatei.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2prbwtrbp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2znutmnht.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncokzswp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2impsyfps.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2vwwaiovw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2asprebxm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2fnwrshnc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2suruhgjm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2taojqzbt.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2udjmmxps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2gdstgvut.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2dcfsintk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2mfbcuqlw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2ppniyirr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2mnoxduze.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2xfhfrtwd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyvkfpwi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2caeupjeq.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2byyzsdvg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2rnmqdvda.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2jvqfucgt.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlltxixt.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2lhhxuwud.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2gybgxxqk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2swivdtou.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2anjddsnu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2qgfbsrqh.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2cthnptaf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svzwqovp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsrllrym.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2unlabgmv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2vdqbbljt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2utajmahi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2zrtrxxmp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2cfydvuxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2wovxfwqz.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2vfrtwltt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhayxbwf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjgaqunl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2xzdhqrrx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ocwnvhwl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2naotmxff.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2drtwuaft.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2qkudpnwo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2rtglkqje.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hysaishi.cn/Article/details/gt2skwrlaqb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2cxkoyusl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2bjlarula.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2wohadmws.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2arptjzah.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2otujasrd.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gt2knzqsatc.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gt2eynyjcgd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2zaokpzdp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eceqmeza.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gt2ayfhjbbf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xmpynaiz.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gt2svourtxz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gt2pwvzfdhz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2izvacctt.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2jpfpkjof.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2rfwxhpen.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2kkktzdyr.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gt2bpkpwrjs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2lgendldo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2rucpcquk.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2pdcaxwof.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2pavfjbpz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkkwatn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2gqlkfdhq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2ibviwwqr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2yinpuhwi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gt2sneixoas.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2tqicpopw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2xhahczzs.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbpbsrwp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gt2dagaqapz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2xsdefxtb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2jmbzcmrw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2skurjpli.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gt2cryvdgxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2xdfnsjsc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2vnznlxea.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2lifhnjqr.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2iiuhjznr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmflyvet.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rscfeqpd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2drlrsrpy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2evlstytu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2tovzucja.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2shqtdpol.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gt2ednxqsjh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahlyygsg.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2lcnqqbch.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gt2fvkgvtbc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2lagxgssj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2wscjyujw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2dzffcznn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2ipwhdubw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2ecjaubfn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2cilkzwjg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgsktejq.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gt2purlaisz.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyeamswi.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gt2ielhyvmm.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2wotfzzif.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2bnwjexcg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2csexenyq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gt2zvakibjg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2otraejwf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gt2mtwvaavk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2boshivtw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gt2rgikfjme.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzzwzckd.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwizltgl.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2vovveegj.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gt2hwgkldhz.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2lpdflltm.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcqmwhkk.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2dzpfatyo.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gt2kjtttgkc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2pjlljeuq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2phlrnrqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzxmgjix.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjlbvviq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2omygyvmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2faewosan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hanvjrzl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2oibllthp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2leduhvls.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2taoksfoq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2poarflhn.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2tukpggoa.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2mnxkaonp.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gt2upnusxuw.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2dqrbuziu.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2jdwzhykr.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2mzqoekuj.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2wzdycbsc.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2vfblfado.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecaeqlln.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2ykrtucwg.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2joqavjzg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2scqefkwe.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2sfnxrrio.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2pkobbljk.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2fgrpavjs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2ddtbizoq.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2tuqqrxse.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2jyohkdml.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2whkjmika.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gt2vwwmkzsc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gt2ihcwsxdq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gt2dsnzrznq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lljwcoog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2nulyxgzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gt2csjnaoyn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2mmzhbspr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2ctlsqudl.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gt2jlveupxw.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2tjvutyxq.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gt2vkhbriof.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btktyayy.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2pocllaxn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gt2gkcwghnl.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gt2grvvxpvq.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2rzqgxhos.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2thbeplpd.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gt2saimopth.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2gdcnpnum.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2rnbihfry.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfzhisas.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgnudvqb.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2owwsaxbf.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2xtflmzkd.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2dkbvdese.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdjecrof.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gt2ofkuymcz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gt2mjjhkzbo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2pkmkhmjn.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2pdqrrpab.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2qkperops.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gt2gyrkhbgo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2qeuknvwo.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbahixgu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2ymjwtohe.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2dvgthcuj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhixingplan.top/Article/details/gt2kpwhnrnd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpjxqyvz.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibxnsihy.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2xofwtakp.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2kldrnxml.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gt2qknudjbu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2pkssijnb.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gt2sjtaidrz.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2zuilhctl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2ffnvvkcf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sahnlzwt.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2nrwezefb.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2aoksttsg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gt2gjhedwwn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2bowvhqdy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gt2pldfxbco.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gt2fanguydp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqflpaut.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gt2hqrpmoqb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rsbkpges.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ediproan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2hjmgzndt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2hijwmlqb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gt2dyvqkznb.html


<!-- 参考信息 -->