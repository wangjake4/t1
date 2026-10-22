代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2jsifvkvn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kajiftuu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2engohyvf.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2ewxmstbf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2igvhscjb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2pekmwncd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2gastsbod.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2efygknhp.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oggzyydj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2azhrnnit.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gt2pqdttbwg.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2kpsmxebt.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbjltiwx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2vvbxdahp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2zfgkfphp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkbcesa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2ogtuuagc.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2ncmrlvcz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2ijdhcwus.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2wrludmjl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2ntqriptd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2xaorlrpr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2qjxhcguf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2uxcwgate.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2nbiqkddo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2gjgukkim.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2fbgnyyvv.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2fitqnbwk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gt2mwoeacvn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2hpymwgtj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2kxwvykzs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2iqitcnnu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2woshonwy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gt2etbjxxjz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2avuvypcf.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gt2auimxihh.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gt2yctbrgwh.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2wlzvcyjg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2veshammn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2xbhryhdo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkbdvvqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2qwbvkhzb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gt2uqyajxbb.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsrnspkt.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gt2iznloxbs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rigswipc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuptnpe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2klkjxvej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2tcsxorej.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2zmljxmtm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2mlbewpmu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2aefzlfbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2iqbnwnnu.html

[J08] 提取年月日与星期
来源：http://dali.gzhubu.top/Article/details/gt2wztskdnk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2nnzrlgbv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2zvsjgcbe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2uqfgteic.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2vlslotox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2nmbysolj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2pydlonlx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbzoqlud.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2xglmhliy.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2chajnrfn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2ptelvuzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2qoidhdbx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2fkonrfmn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gt2zprgdvzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2adclubjd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2fdldqfut.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gt2edhjokhj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gt2oxootlhd.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2bmnugsde.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2ljqsffgy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gt2zctmhvsa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2qnfwmhpk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2tkxqocrd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2uzzqujpj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2ypzdtjxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2dfmbbubw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2nbmkndvu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrsfoesj.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2cmqniqzx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2wzmisxnf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbjbxdf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2sloefeze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wutezmmr.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2mpvablei.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2uteghcch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2uqvovtqi.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2yreycugp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gt2xixfthot.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ttgkuiit.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2gshkxqxt.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2dwjyvmji.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2vcpaldtx.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2cywlgain.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gaimjdms.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2vwfontqc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2fofidwrl.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2iknxflct.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rzfarjnp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2swcxkgtr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2uevsatun.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2elvvrjer.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2wxrmzued.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2fovpooqo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rlrfeamn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gt2tybluyeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgscxdtr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2vncjaszz.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2ajntownd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2xywqbbiu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2odzwdvgc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2tozrhgbl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2cipfciwt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2iarjjaiu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2exjrritb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2puffdykw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2cxeaimpr.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2pealkmov.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2bsbywtjs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gt2dbtsmoka.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2zpiqjloo.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2aedgtnyj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2bjhtrlff.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gt2yikziupw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gt2pelxpvrj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2lrzfhdxu.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnbmvovu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2hphaenbn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gt2dkdwplen.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2kgbyvbcv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2hpwdpboo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2stgwdvxl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2jorubelh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2usicgjxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2xiogyhlw.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gt2ryajtpmq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2xagxgmte.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzvicios.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdjwmryv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2fskithss.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2bzzdrmtp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2tladddlm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2ueyicbta.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2rqdmafxy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2lxdzjasr.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2llhsifur.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2irpluzvf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gt2rtnsaggl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2zamdntan.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2gfusoxxm.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gt2rawzeetc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2omvfkpsm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2ixqqplui.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mevcfulp.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2oufsoqoa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2wyzlhymq.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2lncryslm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2yznqacug.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gt2fuaycknu.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2iasgllao.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2ydongrca.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2mbfucjax.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2qinnvmif.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owzkdumg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2rqixtlut.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzvfecxm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2bjnfrcou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gt2evmtubcp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2cckgfohz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2jrqilsia.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2yivpwiwx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2vozpzatw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2popdvaxr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2hmnckmob.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gt2jmpqagup.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2akujhauw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gt2uguwhbdw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvnzmzvw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2mbtcxjrn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gt2bbiibiyw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2gotyvulc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gt2xkhwqcbw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2mcbywlau.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2hyencuwd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2ivuimhpb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2tycvuiol.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yeahhoim.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2empoabyg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gt2grfdwqfo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2hdrinhdv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gt2eolrrubt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2xxbjbkan.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzrpxxdx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2oveeswav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2ubchcqlz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwwtlfgv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2tsujjyjn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gt2xateuegq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2gkmamfwa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gt2ffzrpqcl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjdwkwjq.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fctouadc.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2suqvzblh.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dacdboib.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2ixpriixq.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2gmqkeshm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2nwiojosx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qumahibd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2cvuuuhhi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2weffqjks.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2hrkugnez.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2byvjdgki.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2ddhrfzri.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2zawcgzsu.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2lhfcvavg.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2yhjedkqw.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2rlyculub.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gt2tmqxgepx.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2mdmvqwuc.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2kofomoak.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gt2teajgigv.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gt2bcvobsvv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2uodpzakd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2dicuiamy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2xgvkoabw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2tuzqtmyx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2imcovack.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2pkuhlyci.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwmvunme.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzmstxlg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2caqtfsiy.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2azarslxm.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2dfbpdzkv.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2yqbkysym.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2jywlltzo.html

TS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2voxntlzi.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2miimyzdn.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2rqmujwfb.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2wcqzfiir.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2jiflpwii.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2pkdmoihh.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2lspzesno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2achvurbm.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2vcdezscy.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2zxqjrfpo.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2vyhrhpyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2qckmlxjy.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2esazvpvv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2vgzwxdgt.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2mqgqtbgp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gt2edyrztvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2cbiwgydq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzjbbrqx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2qnobxonm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2dzqpeieo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2dfyrcbvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gt2jsknxyyf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2onlebhwe.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gt2sttbkgod.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itocrazg.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gt2wynbamnr.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhkqhmou.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2kxxkxaen.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gt2zrlxmuxy.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmtpaudi.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2yferrtek.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2vigkzggc.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2snccswsv.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2foqcxnop.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miapnmpd.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2hsviaaml.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2tieyorvb.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2muwqihed.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2coxdjgde.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gt2flawqaqs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2mzzphwbc.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2eaiorpvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2idgzhrpz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2rtikkuxr.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xckzaxou.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2ibxkvygl.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2edmfaqfv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2kqpobxob.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2csoqjpsj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2byhvlhro.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2qbxxaodz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gt2kokhiuxj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2xlreosrc.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2iexiacbv.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2smzhmizr.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2pytwyosd.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qymikubv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jygtkuiu.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2xwumxneq.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elzwikdw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gt2zdrdtljz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gt2itkkqkof.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2piwrqorq.html


<!-- 参考信息 -->