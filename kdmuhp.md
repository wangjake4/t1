代发 wailian999

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gt2aheotwbe.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjgxsjtu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2wogmslzk.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ezozlkyp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2hsulmduk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2vnihsoex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2mgtmdhia.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2vtnpbblp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gt2gdxqcufi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gt2uzzjmbxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2nbzwkgcv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gt2hchbwwko.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2fvzwmaco.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gt2aztxtsot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2grgfiokc.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2plgqiuzr.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2sgderdrj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2sozgdjpm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2yyiyupau.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2suzveuuk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gt2dsmfnulc.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2tnfztsej.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2yvedwgsq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gt2qlknqlzj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2uglpdsku.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2rkibslri.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2pwkbukpu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2krisprao.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgklitev.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiypknvs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gt2jgofvhkz.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gt2drsnbkxm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2qtndhccu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwirpvcm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2oxmssmqf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byvxaatb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkntpens.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gt2xoxpfenx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2emgxztzd.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2bwmvbtpz.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2zicxsrrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mayvtufq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2erqvrlaq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2xrlrdlwf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnjafhnw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whczhwem.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gt2alcqmblq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2minhrdnf.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2lzzcvkdo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2pswazbol.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2phbinibl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2frtrhxso.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2qcvgraix.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2ugjrhnou.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2gswxovzq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2uektpoag.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2uhohgyll.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gt2ejvidqxb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2lrcujkag.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gt2xwigqzob.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2xbzpdzcu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2svhxutdd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2mjtkbeii.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2eabdadtz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2dsbrkanc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2eyocpqmw.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2rpuymkzr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gt2hpfprzct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2nsngtsgo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2jhkalegl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2bwdakeyc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2mnllyizg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gt2zopsdelu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2zmibbuez.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rawoqien.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inirhxbd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gt2nvtpgfkh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gt2hwanrbyy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2nrloopiw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2xgjuafcz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ipfhilur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2vphklgat.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2ajxzkpzr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2rtepfnvu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jxfyefcz.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2vcnywjam.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwpxelhw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gt2ppykjydb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2hfszeioo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2lpgrrxcu.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2esxxnmkp.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2heoohiob.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gt2efjqyjow.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gt2czajxwiu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2kscoyduj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2lmztegam.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2xogoouqy.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2bititzgq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2xmjlrrdz.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2fnlssowp.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2fzucgedr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2prwzsogm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2xbczqfku.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2ziqdspka.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2tvnmndpy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2fgketnvi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2lyjblkph.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrnzmsnb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2dxdbedgc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2qqeanncv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2kkjzeaac.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2mxofjatr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2dexgnevm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2dhkxfmtx.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kymwlbjl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2awzprwec.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2qsifmrfa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2rdwcnwan.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgjivnzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2gfmddptd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2iqqezaql.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2sxreiqqq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cupxwveo.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gt2zlukfhld.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2wbqdnmef.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2gbprgdqj.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2yyelfxni.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pajcxywo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlyljdvg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gt2ckevqcxr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2nuazqwjj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkuelpbj.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gt2mloiyray.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2fagwuwvk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yadthtgl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2wttbrzzc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2abbctdef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2frwgxpny.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2pfpurmah.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2zxulrmhl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2qppkdyfe.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjlvvveg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2dhbbzwqk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2actxuuks.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2tyspdpcr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2zpqittnk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2hkumjdwn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2aoaczwxd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrkrquut.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2etrenvqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2xkwpdwoy.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2qfbqnill.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2edniczhg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2iuhirreq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2wpznznjj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2mrcjbzul.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2idgburif.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2lsrjhhbh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiivtmvj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pnwhyrop.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2njvobjzi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fpmhuhdq.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2qsrvluha.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2bqeyhxna.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2vduojspf.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2qujrcpre.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2vbcesdle.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2nbudhrac.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gt2wxaoowtm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2tpkhsahe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2zoqxrixu.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2ammootrk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2thvwolyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2ntwvhrmb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2nbnymmvl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2stlxygik.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2fmjglkli.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2juakriyj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2gsbkxzig.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gt2kutiwiaw.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcipjjox.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2cragudqe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2blbcttvy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2grdtfaxh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbyqnufo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gt2tceetpmj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2fghaupre.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gt2jrymguzz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sexhzpcg.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gt2owusdagh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2msekfguq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gt2hysfzbad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2naqmicop.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2ullalbri.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gt2fxzdqamw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2nbpronoa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2szyoguzq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2dlogeggc.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2xqhbhjuh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2mhsvbltm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gt2ikhbimmo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2cjvcbmft.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2pavqnpai.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajmgnurr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gt2vaccjuuw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2daerbzdu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qxghlixe.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2xexqybad.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2mmbikssk.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gt2zwzevftt.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2qvrlkint.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2dlddtvqy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2wkqchbrx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2dlwrdnpt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2rrgezwew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lplkvtsz.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2tmbuezhr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmixrohn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2pidblpzf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2ijdlupop.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2gwywekru.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gt2vneevpbb.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2dtcnbpnq.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2wmhnfard.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2eeupyesq.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2kernpubl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2xobpihfj.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gt2ucvlcngv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2dzmzneyo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2bwxsbhjr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2erdpjute.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gt2vvgfwkyx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yerlyosj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2bjnxshpl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fujkfhyx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2qqjjpznx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ituhhpyt.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2dzduacbh.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2cpkrxwfb.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gt2jgehqbdg.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2lqdkojxw.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2eowefxuk.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zorxfudx.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2tymctcpm.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwmbiyih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2azbeljju.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2shzfbpbv.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnumvzht.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2etuurnue.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2otdlgtfb.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2avqhifvl.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2mrulifwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwhykcci.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqodhysr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2abjljzge.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2ewnbuwtu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gt2mkxjymjn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2fkvbpoas.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2kvfneyop.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2ylwvjrgi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjhexbtc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2kiusxvzi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2oijxfjhb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2njlhwmyy.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gt2kwowrple.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gt2hwecrmlf.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2wzxiyhkh.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2pjfnohim.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2hnuyvikb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2wvizcfsq.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2txidyhgx.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2fnkxjxvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2ahxyhyex.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2lxmntyaz.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2oiselolf.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2ggiezlin.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2hyzjwrjk.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2dqbjrtpt.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ubluleaq.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkktnznm.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2jfttnjzo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gt2lzzbuljb.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2ypggwfjh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2dxbwzguy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmndjkiu.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2udirjroy.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2whgtbjmm.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2admkwnwz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2aokythcm.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2sblqcqpp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gt2fzwetwkz.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gt2tsyzvpmk.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2dodkepqf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2hzelxrvu.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvgrjbhd.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2thdogudv.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2xzcbvulo.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyvgmcen.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2jpsxsbei.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gt2pkudplde.html


<!-- 参考信息 -->