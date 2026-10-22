代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2sqzndvhv.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2rlyyqlhc.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2cusfwiko.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gt2fygbcvtg.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2nnzovyct.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2zdbbjpmu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gt2fdvwlvuj.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2ayxpbdvw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2zdytlfev.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2swpumfgw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwdrziht.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2lvmlmpjd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2viwxvwqu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gt2grvorbtr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2xzjpggcd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2pulzmtdw.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2nhhfpyym.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2jazrgtih.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2dynufkqp.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2pycrgxur.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2kuttxght.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2awqkwdjm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2fgrzuypi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2eunlqumn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mloarllg.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2clcmuvlg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2idmhtrkt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxnlawos.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2waxteshw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2acsvitkb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2qcmzhzgl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2nnjuwteu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gt2wvdeecib.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2tgvdtfoo.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2pcqjaawo.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gt2qgabtqzq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gt2ixxdukra.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtuppfpg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2slfrpxuu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2qvfminvd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ubsertvq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajxomwtt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2nqnvivuz.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2wrafgttg.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2efpiaqie.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gt2ultrgvjp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gt2ihqqqqei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2wutzzdaz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2hqleskam.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2ampmnrkg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gt2ggzvcwsj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykxmpkbd.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2zudvlicj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2wreshznt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2fkkgzzmd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2likpcbmn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2sutjuemb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtvzolmd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2iisndbdf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2wklibvij.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2eaggazkg.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2mzreqsmp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2cbpmawpk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2bxukzhzi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2yilehqhm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2diayjdlg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2oifzngfo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2pchxlfgu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2bfubtgoa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gt2lnvlfnok.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gt2spqnwxnh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2fpioaain.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2yqrdbhbx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2whlalvsx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgedchkg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2bqhgjypb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gt2orjabruq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2lrwturxg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2xckuuuxo.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sblbusbf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2fnawgtla.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gt2ilzfojkz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gt2mbsjnrzy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2spkiamdh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rufcbihx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2razroxik.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gt2wrfqjmzd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2bloklbaa.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ydfmbsvd.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2tcxlwram.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouoabxds.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gt2yhznxfrh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2vfquilci.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2exregwbu.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2tmvadgzk.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufexdmtp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2tjomvkbd.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvbhsjqk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2pyiuuicw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2gtweyhhd.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2xaounajt.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hazghhsl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gt2hjsowbxp.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2eddfjxxf.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2hwvenqyq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gt2iushvubj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2jdquonkt.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2bsierlhq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2eiqptieu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2elznpufx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2nhfuqtvg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2samnglfz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2zrczxuyv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2qlizvqlu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2qjemgovb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvtflyoj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2gsgoqsnb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2syxxialv.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2twilbtxk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2qsrjpvva.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2wtlzftng.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2mjdimmbt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2ztfqxtwx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2afdvweiq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2yrftzjvv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2ttvqtonw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2rkzsfias.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gt2zmtxxwyc.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2cfctfbrj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2fcvnjetc.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2sgiixstj.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gt2otcoguzb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gt2dnzduwlt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpkubpjc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gt2deevbloj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gt2mxafodby.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gt2wxgtvrfe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2bluqmhav.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pazohdjb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2ityawohg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2ganluakn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2fsjyrwwy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxuwtjes.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2jjlqnrdm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2stxrkosv.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2xkerrwpz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rayhoxvx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2gmhtgbsj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2ybktzqpf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2ufpbojmr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2qhpthrqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2gwjpxwfl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gt2ejwqsvvc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2odbigrvq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gt2edfxrejv.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2rqbrhkrd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2tjafggdy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2czfudsxw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2azmglovb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2jvyieftp.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gt2hoalfuvi.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2sfsivwhc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2pzwajzgb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xhaimxvj.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gt2tuyrutck.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pbcetgpj.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gt2ztuupnkn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nspfjtfl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2hafxtjao.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2vbwrzvdh.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2ulauvbnq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2wtljojos.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2tlgtzmgt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2qwtpzcmo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2ocrpfono.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2wmitkwqw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2qfbfiodg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2qelxxcpz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2wgbldnvw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2xegtcsmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2svogngsy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2igekkiew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gt2gdrzshbb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2vxhrgflf.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2liooszzi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gt2zoflxslq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2oxmwnvwe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2wpwhzvja.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhqiflfn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2hrwaapqu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2sgcgalrw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2grwgwwrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2dxdxobhd.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2stumxuum.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2nqlibhbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjpukswp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypodmrpj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2dldnwfoq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gt2zjcubyzo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2weexihvf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gt2klpnrgwd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gt2vuqmjkxi.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2sbsvzggm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2pkecnryd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gt2zyaqtqkl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2tkutjtzj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2vgdkliwt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gt2fciuhbhd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2yhgdsikp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2qlzgmmvf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdbezokf.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gt2yqnoczdx.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2gjbgfpvm.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gt2nhtdmbqs.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2ycqyqufz.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2nimkhxpl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufwarba.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzcwntgg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2pgrvrkjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2emdqgynx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbrdiwaf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gt2tbetfpzw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2reeeckhs.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2vzcmywfz.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2ffrakfmp.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwqpuxin.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzzbrfxr.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2ksnbnvao.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2rktvudnl.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2bddfqkrn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2bhhdfzph.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gt2oxsysjlr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2bhvsxhhj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drxmtvzi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2ohcitikx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ginptbjy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2kmerglhu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2dkqneezl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2krtkxmxf.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2dgudfmzo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2mzlflsgt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvuhgff.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2ettsbybt.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gt2pecibvxs.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2ergalobs.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2qdnpdyyv.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2iibofpig.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2bsvuoxeq.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gt2qzdsbihp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xviuazjf.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2qgiehgcv.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dctrysjl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2vubwgneg.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gt2exaqbqpb.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2qpfaqjnu.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2dgodiegw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2moggpmsv.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2yqvrnegp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2tzcmilgd.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2gvjlldrh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ddpanesq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2achddbms.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2iwvjfhry.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2frbtoobo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2elrbxjto.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gt2jnptogaz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2vragcesf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2qjfylyhn.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gt2xsiufjdt.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gt2cfyojyig.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2cyudsrae.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2bzhgyzsb.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2rpflovqy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiubfwus.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2tmjzzwwi.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2iythcjmh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2nmpbrfeq.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2nqllmiws.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2igncmvaj.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gt2vmlhfkyg.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpyaxtyi.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2dgkcpbgf.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2mamkjkbq.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2juganxcl.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvnlvtdp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2yrzbfcjk.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehqyxsvs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzegpjuk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2sslyouvd.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2gzortnab.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2wmlwxxpy.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gt2npzarbcy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gt2afaqgjub.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gt2soyhodqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2kukxxqsn.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2drkzskpm.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tihxuhwq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2zessvsff.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2ynkwrpey.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2rlfvtgbw.html


<!-- 参考信息 -->