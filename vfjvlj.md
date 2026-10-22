代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2bazcluze.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gt2scljstmt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2ftpxbvfq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2dyvuuhfy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gt2ixdhtmuc.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2pexfswxu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2czapvwna.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gt2lmvmbumb.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccvjwsft.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2frrgbcjc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gt2ykfifodx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2ilnynyjh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2vyorhqsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2hdbduior.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2erseciyt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2aclufvqi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2mlzniwqi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2tvzzaeml.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuvywxac.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2xhxqakpv.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2peciaxhm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2cabzboof.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2ooqvkusy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gt2kjuhrbbc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2tspawnco.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2zkhhjksy.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2ngjisiiq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gt2ubjxxqks.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2ywrezzhv.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gt2skwstgst.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2acczstrb.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2xwlssvms.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2ybmhvqzs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyalmfkb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2navrcxiz.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2ckofxbok.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2ekmsjcud.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2ifhbnjah.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2faamheqa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2kqhnsmnm.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gt2lcjfdbnd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2bbyftyre.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esvpdapt.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2rpolpgey.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2wjjdybnr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2vpoygwnw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2lsitmcni.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqscofxf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2ltrldvtu.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2jmqqiliq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqesalqw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2fjjqtcoy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2vvquvhrg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2ufxwvygt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2czrpkmuu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2hrrlllnz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2zdkawthd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2dyhulzxm.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2jnbvnbqz.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqhpclab.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2xfvvlnob.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2zcjugcjy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2prmsbrsp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2nvzojsua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjpctudr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2vqyrnugk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2zglowfcq.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2ovbftfuk.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2geaqmykf.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeczzley.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amlmvaei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2nalpnpss.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2sevttmne.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2aqrebzgp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gt2zrmbncfn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gt2mwfzrewa.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2rzminjop.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2rphpinav.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gt2mopjctex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2hqrgxlgk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2ooddamji.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2zavgefng.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2rkyxjizg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2ubmnjwif.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntheampl.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2vpabnzvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hfpthk.cn/Article/details/gt2oogymmmt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2ydxdznru.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2cemlfvxd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxproozq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gt2skpggihm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2ydptyoro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2jvssahdv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcqjuyna.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2tjznggtf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2mixmtyeo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2bdcgqrol.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2hvhorumv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gt2ndgottbz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gt2jgstoedz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2smgknyzm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2kjdkoaux.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2dzaxknpp.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2wztllhrr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gt2eaiocnkp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2dvvmtahd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2akejalae.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2ycnoamyt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gt2zixgiorj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gt2lmmffmod.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2guealbhh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2fpogxwqq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jckrnoue.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2zclovxfg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqpnutec.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2ocwkyxgc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2ktnpnmdw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2hkaxjvrl.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2ilgamsvg.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2dtmxywgl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gt2pisumljs.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2ceufjmwa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2qoailcgx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2twuyjfvk.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2xxaoiwxg.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2litbcqlc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2txzgdugk.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2bbjrefbp.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yzpvlpzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahwxoenh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2beyadjuz.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjmjrbjz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ghdncsao.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiwbfyh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2ziabpxaz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2raqrgkkj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2tqottvtx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crasmkrp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2ygeadunu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bazrapti.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2zpnwhbqc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2rjlmrzki.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2xgrdqbht.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mqvuoguh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwnzgcht.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2ntlghnuf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cejsbrcx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2wzohrgpf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2ftsojqzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2gahyfxwl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2wtzwlskf.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2hmwpmjrj.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qskghmtv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gt2lfdshygm.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2kvpcqckb.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2dhyeiome.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2toxdldoy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2zhzenwpr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2yngusuft.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2gvzfyrep.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2vbgfqjse.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2jvlpsggr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2oqaqdips.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2gvnjuphh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2kamzbxsm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2oppypcvn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2dohfhjxy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttccvqvx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2cctezedn.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2denbakev.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2jsjsyzda.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewcibzxm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2ahimsvvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2bjozkdwd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2jthzjyrq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2wpfhyfku.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gt2maannhga.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odviwmjw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gt2rapsktsh.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2umzfksvi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gt2qpnswfdw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2eanxmlyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgpruzkb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwmwxfif.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gt2ugvptywl.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbjeljqi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2lovsswnr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2zihxedvj.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxxksuxt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jzjdgwmt.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gt2clysgojg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2snapsluu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gt2iccqoquy.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2birijexc.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2zhkmurad.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2maqguecw.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqkpgyni.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2upfexivk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2mexlsgxo.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2nqauhjdj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2eitwghhr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2jfaswmfu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2cdvlaldb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2ghobypln.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2cdttywrd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2opspdnfj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2eppozwfa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pojveoff.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2umrbgnvm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2dgxgyipm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2vrhnhsbn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gt2ulmmckje.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2rvcskepl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2dgubucua.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2oknfwhez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftrcdagz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2xoaaamxi.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2avruqdot.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gt2grikgsta.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2nupuaonu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2qivykyja.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2ozhifzpz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2olbygltz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2ctvjyknt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gt2wnwcwziu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2ojcwumcg.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gt2injtycac.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzfikpig.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gt2jswhhgaj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2iibbhszc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2fifbwoyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2xuaojihq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gt2eeywcdfq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2pukomift.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2qpfjyoud.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2jmkdqokv.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2lzmweujt.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gt2msazrxap.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2frhpjujb.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2pgqennom.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2xnqqyjrq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjmaodhi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2gejaebaj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2dyzpyzde.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dysiuscx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2qatytfpy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2mlojjsdn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2zyjfbvnz.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkvrnnch.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlrkqbal.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbovonl.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2ezxzthoq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjxluwn.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2okdhqxti.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2qfhbtgbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2gmavtddu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2eonffsul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2ermjvakh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2nefwhpbn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2ivnksemc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2lvgnqztd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2lojmgvof.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vsythuaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gt2jervbtix.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ifatyvob.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2jusesjpw.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2luogmoau.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2pqzxjyds.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2usqbamtf.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zokyljtc.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2hhpqnxfs.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2dovrjown.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2tqhwedze.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2vxoqmgpq.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2degmlugi.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2uhnvigqq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2xtdvvaeq.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2vmvffzfh.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2ayksufeh.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2qlfhcvls.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2qmiiyfcv.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2yzwxrwru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2qahdpmxg.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2pndrhmav.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gt2rcrjgrrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2ekncinzv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2glypvczx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2trfmfdmz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2xcbzcnil.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obxbybbi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqwujeyi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gt2ihsctyto.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gt2moidhlxr.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2jupubvdi.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2owhjnqwa.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uluamztn.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2lvdriqkl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2foejkxfm.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2exvjilrm.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbiekwcb.html


<!-- 参考信息 -->