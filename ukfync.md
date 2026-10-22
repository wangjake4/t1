代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2zitemikn.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2zdbtlvhf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gt2lurdspho.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2zdvtffhu.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idimxjlw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2nemtbmct.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gt2phtvwxym.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gt2kvccedri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2tosinymu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2phhjnlzq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2aemctwbk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2xchwymjy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2unddfivv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gt2tmxawpnc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2oayyagoo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kypbeiiz.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gt2ucaxrdpw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzslikft.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2waztrkhj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2wqcovbqp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvolawas.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2zvxflklx.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2xxhjkxvc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2fyutlitn.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gt2ezrwbkns.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2igukgfck.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gt2vnuvtvej.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2avmbrrrk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2dbdopyim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2mbphmehl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gt2nwhnegkj.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2kzyinocp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2wmfdxfwf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2zumysmko.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2sksrfmhd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2gobehcic.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjgxogxp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwnxqyeq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gt2lsalqrxh.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2jpnehyqh.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2omfdakce.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2rtikayhj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2hbsfyujz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2qlspjhft.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2rpsmmqvp.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2fooetipg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2bbrxzndk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouseuwzv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2pyohnfer.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2pvdkjcbk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2xrtlthxq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gt2vpnlxdop.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2ffsasrsp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2smgolpen.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2xebinral.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2bfgbhwvk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucsxntbt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2nlaznidv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2soqxaodm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2wnnnnchk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgexazd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2rinhbjns.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2nrmkgywy.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2ngicwafd.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2xujiuzei.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2xikmwbbw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gt2foeefjcn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2owbpzldl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2tzxjniwx.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2psjlvuvj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gt2kvvhobdw.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gt2myemxira.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2lnirilso.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2lmgogmfh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqxdplyr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2ztnnyamd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgbtbkip.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2hzctkdjm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2kdniatgz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2jivqqari.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2ciwbhbzj.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2iaiokjbs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2irjrxtbf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2wnowxrpb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gt2qbzxilzf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gt2idgmpvvt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gt2ixgxqadq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2uwvdmgsp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2xxbmaysa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gt2muzxnyuz.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbrmkhmq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2codjqufa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gt2zcnblufw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdxfvilk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2ecibbhtu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2orfagqpx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2wjzuczrv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gt2uwajtpbo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2bekmpyoe.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2ulmbvkfe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2lsezxwal.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtvnmrsv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2aizwjffg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2earzglef.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gt2rvsuubty.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brdqpesy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2pyqzifkw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2skutvnko.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vmezquve.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjjbxarb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hsschmse.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gt2binyrkss.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2gtwgkcxm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2alueeeyg.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2uipygzeb.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2ryfiavkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2twphibck.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2gnwnkeqa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2hkhvnynp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ddtbqqqq.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gt2ticfafxa.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2xfxhyzzv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2cjgovuav.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2ogenahrg.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2awwknqpx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvdvkbks.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2ixvzdeab.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2myrqitpw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ytswkeht.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2tslfdgao.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2jdqlmvue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmdnttux.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2mrimpizv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2jvjkxozy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2amvfqasx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2bsqtfaik.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pghgdjit.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvlzkobb.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2bbwpqdmx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2ncnkfeme.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gt2bumqkdjj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfczhsdt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2xfjomjep.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrvjbmfi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnjomesw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2trxxjnxl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2vvspvhji.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2swiiojkq.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2jurdeocw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gt2txmixzer.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2mdmyabia.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2mtlvwsqw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqozpmpe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gt2xujjzdns.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gt2jpiprwqt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxtdhciz.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2wnxnlyjb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2ulwhwyrs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gt2lwovyocu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2ngwaeuym.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2ycjwbiel.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2jaicnwxe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2csulablr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2mxypsfnx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2qotnyiaz.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2mmkuokcs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkfnthen.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gt2svwaxvue.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2mtwvbsek.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2imsayvsa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2zzljpahq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2rkopaymd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2lumyexia.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2phurbpwp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gt2ozfppbch.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2uqizhsor.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2wjcjxlqo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2tkhqmcgl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2ftroftwg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2xjdywrif.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gt2jzsbrpde.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2pzktaujt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2uxczckxo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2oobxiefc.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2rgixfkgy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xkltkyzp.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gt2zmlvylhv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2pmcpolam.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gt2yehkvnws.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2alrpoozp.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2ssxxnfit.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2nkpvwbxi.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwzxqpes.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zntggmqu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnfvblqp.html

[L02] 发送 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2ybrmmizi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2qwfwvqaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2tgmzsgdj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2gkazjzqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2mizdnmrp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2poycvgnw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxwiyxe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gt2ncydlifu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2yycgfpoc.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gt2ivnxyznc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gt2ricihsgx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdrbcrxf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2lehnosdq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gt2ktfspbej.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2sgleoets.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2uhyyazwa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhcggnrq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2vctrnhpy.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2yqasnkyd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2bkwqrmaa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2wcnjtftc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2qawodflw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2ugtukrjc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2svssvvkk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlpwxtq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpuohlwi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2hujxezrf.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2fmryimyc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gt2vpoqoymk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gt2xoflntlj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2phfjoxqr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2ffmmzzrr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gt2festkvsl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2lsxgoyev.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gt2pvmvunep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2jxvcktxe.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2lrzxxxxk.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2qlksxbde.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gt2bcdzkjrc.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2tdvogibr.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2qbhqtzxm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpudujsu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gt2eaiguqpj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gt2jypuktlf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gt2qicetjvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2yhvwjelw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2qmqgujip.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2vxoqbmck.html

JS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2wtmynwzp.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2zclhefdy.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2bkwezgwa.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2qtpohlvt.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2iqlcvkfc.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2loedmcyb.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvrylryo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2stjbrmcs.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvduqlqq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2regivavn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2vyrvnxwa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2wyhecorm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gt2dkzkiaow.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gt2scbqbkmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2xfvpsbkp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvnarbae.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2nvdoyqqq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ytxrhmwp.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2snptlidq.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2pvejgsky.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrbqhjki.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcttyspp.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2gwkohkjs.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2evpzbghb.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trrhstqb.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2anjfdcfy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2vaszwglm.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2oramtzau.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2aahdnmwy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2gxegetlz.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2aqrawwqs.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2frgvxzmp.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2nacjhqrw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2pwxdzcav.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2azchigmz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2vpnawnkx.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2ijmehcvl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2gfqotkmg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gt2aolynvqb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2xoihzvwj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2rjesyjoa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gt2vlfgbnlz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2yyosyypm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2udnvfbfi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gt2olxvniwo.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2oadakpmt.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gt2zmsabczn.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2sysfzmhb.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2pkpthftr.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxrswqwk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gt2nbimkxrl.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2diljbmst.html

Ruby: Dir.pwd
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqmoyvsv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quawzijr.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2bwidpxsf.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2hkghckdw.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2ksiwlftw.html


<!-- 参考信息 -->