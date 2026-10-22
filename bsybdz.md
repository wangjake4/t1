代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2hbfxtndx.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2kusbuqsm.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2xqwupgyf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2kuupnrrb.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gt2gjnycvvt.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqkgbmfj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2ldwrmboj.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2myweplwy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2qtsryywe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2bqaoxiny.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2gftwmgsw.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2ksmrsvlo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2aqqxfxog.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eadamqnm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2ldovrojx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2ttwaqvyy.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2qguzeobl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2sbbfsaaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2etsigytb.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2wtdoirwc.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2cxthtuhw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2dxbptlot.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2ibjqhkne.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2hzzsukgh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gt2fgiyrocf.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiopvnqt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2oglytbkm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gt2xgqlfpoo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2fjiyzgwb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gt2gdpzdlsw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2byriudcj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2ptjutuhu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmgtnejf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fohwvodt.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2ceypllxo.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2bcyoppxo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwenldoo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2ftufksvj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2hgjkuahi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2dcbeqzyw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2qmnbednp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2ifiensbx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2flwhfagm.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2twvokybd.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2bkqtqdww.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gscqznwb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2aevdjpno.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2cboiphyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2zwqiwqex.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2qpccuvlq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2hbknfctl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gt2hntiajxt.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2ugevllyb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gt2nsuielok.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2iqcaetgt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2thssljte.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2lbocbpfv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2whonotsj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2ituchajh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2kfuwbaxm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2pjvlfvwj.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2hjedqcwd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqfupxbl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2zahigevv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2zfbuogdl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gt2xzsfdyty.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2aaghrpki.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2xcozxekm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gt2lzyjzmnp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2leryfyyw.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2vrdmjumh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2qcnevsmy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2hwnpllpk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2svjepwsi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2mjqsiyva.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2tgwtmaxl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vneypmff.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2sjvyxbgo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gt2drqgqowh.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2ervcpfvt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gt2kklqizfw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxkuqfrg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2uvufoysq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2puzqxmaf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2edkwxocx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gt2cypevrdb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lobkhtak.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2ciwpfcul.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vtlxkrgx.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2rqvvjjsu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ysfyqsqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2jkpjdltt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2geugszes.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yntpeldb.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2hthqkzjq.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2twuoxmqt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcyswvle.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ibgugbuu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2ztttprzn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmgmeeqd.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gt2wqszlhyx.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2goukxghu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2doakuewb.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2bgumruyw.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2xzyaihtk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2rijzgmmc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2kkdskgbl.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jnulgwuw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2rzkwpcyh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2stnnkpnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2hungdhdv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2avqfdyxx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2kvneflzx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2xqfhlxcd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ofitjrfu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2kgzqqxjx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gpbuakmo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2paornoef.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2ajnapvtv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gt2jpaqjybk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqwihaqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2oarvmydo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2fhrocuuv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2svtvauor.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2lsknfnji.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2uafjseom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdrzsbh.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2ztssxafx.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2xtmfqhlp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flkwsyne.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2hqoreaix.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2dgyeuwgr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2nwajddsb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2npefguvp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2zwlyisdn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2easpwmwj.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gt2braqekwo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2yzilmztp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2grxlnnqs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2gvplywyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2dzlxwgja.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2qyrhfyaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgxpprk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2pqcidepk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2nqwqruyw.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2zonskeii.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2zzbbzmyi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gt2clerfqtl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2jvazdyct.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2mhtpfaav.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2qmfnqjrj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2omkohqoy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gt2nvtuiwbh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2uypjouyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2umnbtmso.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2reuwmvdl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2bymyltdp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2ovhxdhru.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2ddckthbm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2wugzvslz.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2rmjmwjyx.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvcalmgj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2eohevtdk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gwxkdpht.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2xakngdqm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xbnnozsb.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gt2lkcixegp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2ftrowcoh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gt2wmmvzcwi.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2jallmyzr.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2qfhuwrvl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvevzuja.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2zcgeznqt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxubzfgj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gt2pusnseyl.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2julqaltn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2mulmmhqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gt2frprfnfq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2nbquuidj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzruiyk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2ykxlklhk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gt2paacuiyn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gt2ewljenpt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2bgrkdmmr.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gt2ckzqhbtp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvnqvlsg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2xbqvksan.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2libvrmpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2wxvgcmmg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gt2nsmzshmw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2fusdxdum.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2kvottjli.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2pnxcygbl.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2ddbwsunl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2psvuzwmd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2avaxjrly.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2xbpcychg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2pbrkhyag.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2botcbbfp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2aooqxfyv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffpzgaso.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gt2dauhofgr.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2dcpznavy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gt2jezgdaad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2bnmeacrf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2eyaemash.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snjjshiw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2eefcalsv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2hxejvkbl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2aoovdfqi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2ofnusxpv.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2rovtvodx.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2btpxzryd.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2pkearqxa.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2qcoivppc.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2vhrtubsf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2uljqfnxg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2kqmahhun.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2mynqyiyd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2xcydsaev.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2evifoldy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2dbkgfwqz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gt2utytcmpa.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2tdvafzzt.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2gimkxqas.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2ziwubdnp.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2sfowvybk.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2yzghfcnf.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2zuixiuey.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2ltltuxqz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2drowbxld.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gt2wabdednp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2buobtlcf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2taipgphh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2zwaxdzup.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2ntaqlkql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2yfmfztld.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2tnjfgmhk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2cuxbieju.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebnojgsj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ovljcwpl.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2spsponsn.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2anoqobxm.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gt2kxjvgglb.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2kigxvuwc.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2fazhkuie.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ardptfxj.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2mopohzmh.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2xwuzdqlz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2upuwukpb.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2yqppczqj.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2wssedglf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2owgpgoia.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2dxvcwkpx.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2sevuztsf.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2aflispbk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2ftxvipeq.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2gekmddwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2engjvzll.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2oeeekudo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2zbnbkvtj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gt2bceebdkh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2fwqqemgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2agovyrml.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2djnufjdc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gt2qsvfscuw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2okmzedji.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2mldyviip.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2akdpbkio.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwomvhnw.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2biunzoox.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqvewouo.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2oiedsarp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2aofwwwrq.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2sobrwvfk.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2gyddtwts.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2obowwnqa.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gt2prurqzkm.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2jcinlpts.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2ddmlurbz.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2yddardhg.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2okqpglft.html

Java: System.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2raycldgh.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpvludhc.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gt2gfgabpul.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2hxmntbhq.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2ajkklazg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2eauehdcj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2hvtsbsbz.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqtbfuit.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uahngybw.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2huwxebjr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2rvshlcll.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gt2jezslkad.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2lvdrzues.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gt2jyhruwfo.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gt2dapvejvy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2xzipltvn.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gt2necidzla.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2twktcbey.html


<!-- 参考信息 -->