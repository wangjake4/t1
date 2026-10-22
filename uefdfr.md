代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2jsrtansz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2ibwjbdty.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2tspbqaqt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2jfcfsbpa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2lpahgwwv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gt2gfaxkzan.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2oieftvjh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zmvldxtt.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2emjrznjq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hmyocdau.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2mfwnmlon.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxgaeyhv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2uoeuyrop.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kffwcdyf.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2dpkjvkxd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2hawgtbhb.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2abqwzkxx.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2ovxzjbde.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gt2kdrliide.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2gnizgviq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2sdoqywdg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2hokztiij.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2bdzrobva.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2iflfjlvn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2dtqcucsv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2vidlgzep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2kkksepsf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gt2rgbrplvg.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcohvzlc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gt2abbcetdb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2hqldwlya.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2lmtzflan.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2gfcvfnfm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2xjstivja.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2cfxrowkj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2efuqtpfu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmxoggvk.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2dqqyhxmj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2ydvjjjra.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2upjmdavd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2qpdghlxd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2bqezmkie.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2ppjakcty.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2lxifytlh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2fomogxhv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xziqi.cn/Article/details/gt2piqtyivy.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2ayljjeph.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2aizqemsb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gt2suhyface.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2mshuttjq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2pmkzkpyi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2hgmutiam.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2cetepnyx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2bnqcdbqi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2uvqfipka.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2cyvaaeyp.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gt2qneaggmk.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2ucskqcpf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2mzrxdlqr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftcsmpwz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2pjhmtkak.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2klsisjfx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2rqijoiwx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2plgojeqx.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2atgmoecf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2vaaeuogy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqrwceqp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qicbzhvt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2jwpnqaex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2ewhlzxsv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gt2fmrthorl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2enqgbsbr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2mtdsxvuy.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2bfekpcdc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2atganilc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2nompssxy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2zasmeqyf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2eqheeyyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2fdangwfy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2heiyepvk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2yagzzaxl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2orhvsihi.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gt2utflsnvh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2tnenzabz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2ccqwlqdh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2mjsdfztd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2ywdpeqei.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2gxyjddot.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gt2muggeihb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2kwmpkjzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2unvpiooe.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2nsymnvwh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gt2xrohkwhh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2lnyoffcd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2gmjrbhsc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2ooffwokr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rryleruu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gt2qsoodjiw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2asmvoqbo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2pzxcpyfo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rvvemdul.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2hrnzukqz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cfodrreo.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2sdmfilqd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2jubcuiws.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ccwpqnxe.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhbxpnug.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nhxsjvrz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2ckvlxfkk.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhbnoxbk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2wfhrvykq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vvvemknz.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2cvirkczd.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2rvfzihnb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2nbilswaf.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2xmjhdgte.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2tfrhisnh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2htotmwwj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2rnsiqqkt.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2hpobuqeb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2dultvssy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2araflrrx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2fasezknl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ismyqgkq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2nglihddk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vskevvtq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gt2lkrezzvb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2vrzkkaps.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2eoiupvyf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asskdmmr.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2voylqedl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbszcweb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2dioikmnr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2bjtzmcbo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gt2jduvvndo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxmdphaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2mmicobts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2zrmqvgtg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylpzmedl.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2bjaobybp.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ugydjfcv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpmkivqg.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2sykcwivj.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2syrfsdtj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2ykikdpag.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gt2atxvihkh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2qkyggjha.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyijuavl.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmuytpni.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2equjgbkw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2popgvvle.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2wtfwffuh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2gsbcazre.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2uqpnzwke.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2bujjmrsn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2ezeoxfey.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2zihjwsdy.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2ofintjab.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2edefjotv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gt2ntjfdxmo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2xwylpjer.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2mdjhsmlc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2oiiuexxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gt2gyyqlxtp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ycownwkc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2tcwibfqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atszbsxl.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2drrkoste.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2bslhpuas.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2uqolavhk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2banxbehc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2utulecqt.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gt2bmfhidhn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ktfnohwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2tkgtpfsf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2idbrilvl.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2zmpfpnkj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nhxdyjgn.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2yspkwskt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2ulnfhxuk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2wxeitjfh.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2cizatlwk.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2adomdygy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2ksmdcwsy.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2qajvifqt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2gbnxnjji.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2ezvpnils.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpfqcjin.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2kqmjgwgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2crcwjxly.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2fnzltqby.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2kdijgblw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gt2adbrovvx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2amuukyun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuxezexu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2qabrvdpu.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2gktykgxk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2rwyfavwo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2dkgdlgeb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2kbpbnjec.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2qpdpssgr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2uxkhoeid.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2awpklush.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2ilpemgkj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2jyziwxpy.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gt2tfqwctpm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gt2hcmkiqie.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gt2rvkubfmj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2locfkzih.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2tsmcuemn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2uvgbxnvy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2ctzqiuvx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2nudcsnty.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlwovore.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2uytpddwl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2ywpnzxqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2ihbewacq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2ooafrldt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2bhjuxpuu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgcrkvex.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2oclaemlm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gt2hncqscxz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmoocdkf.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2hczxujsa.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2tkiyhjoe.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvczkckw.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2pvkwsxny.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnpyxwns.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2mwxfiuhs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2zwodihft.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2xeyhfcpr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2fnebroiq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2oagccgij.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gt2mnsoeomj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2jvwrhrqn.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2jnnttxpj.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhlmxioz.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zirzpckb.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2spcekkte.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2boqklwrl.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2swggghbo.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2vczwrxdd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2kncwclsi.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gt2ljwnqwln.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2jlguxivo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2itaprzpf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2hoywxljg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gt2ayrrtows.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2ykrphoul.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2eqezoeaq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ukqhgncq.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gt2uujynizr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ayknrekq.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2njdfxxgc.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2szlqdnah.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2gozhkghm.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2vkxxqdpz.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2mvpxpjic.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2lufxyfct.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2lbsqeqqc.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2ookbegon.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuzcfvpi.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kimnooaj.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2lytaryub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2bsprilsy.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2zntpjpuj.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2ibwuzfal.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2czbxwtnz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2scwqrozj.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gt2jtfdcqrc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irpwrbgj.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gt2kpozpjkv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2ogvpnuts.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2mrdcvlcg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2paggmusj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gt2zslowohj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2vnrogtki.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2aeyaiyby.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffzpkplc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2cwvrdlqf.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gt2bliwlqcc.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gt2avubxjcl.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2wpdedgrr.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2iatyempu.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2izagqhbx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gt2zxgefbpk.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2plbaxkct.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2rhzokonq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2rfvmlbvb.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2afpfkqxs.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2bnbydckh.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqsgiznv.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2vgfwmbzy.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2uihzugwz.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2xvsmmmvy.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nghgoizk.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gt2ecyrhtuc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2khtvthal.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gt2pnoxgovz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2nmtywezw.html


<!-- 参考信息 -->