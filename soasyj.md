代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2bzsmdvxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2rjrdbvwc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2toxglimz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2qszckual.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suxogoox.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2lydhadyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2wtclhcjr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2rnucnopx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2vzvlomhf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2diaeablc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gt2vxslgsng.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2ykggcqhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjqipqjv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxxpobpx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2xhogkkjj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gt2sxncrxtp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2nwttgdpn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gt2abvjccnx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gt2dzfkmpbb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2bvrpbriz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2dhluzqht.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2ljjifbza.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2dciyvome.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lafrbvdd.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2ikaykduh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2ssddigis.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gt2wuirhfpb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2dlaaxarz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2beeingog.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2cgaudopx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gatxutdg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2awacnhop.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eizepcep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2hgjpvrxz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2nudumtll.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wxlgsddx.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2gvvwzzke.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qzvizalo.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2wrttjlnk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2hobwxlyx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gt2zuntrrju.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2sprsleva.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2rywrwvcz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gt2ipqfrmyu.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2fyfsohtp.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2pdyfzsyv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2kkuiifrc.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2qcyyxerv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2tassreps.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2ekfjntzc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2thzzaysc.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2fpazsrfk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2qkudvcpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2dfvwnbvc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2rwewylqg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2yzybfbmf.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2ddqhufcm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gt2newwopvq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gt2ghkrujql.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2rjzkkvpm.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqlyfksz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2trxlchko.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2gsjculmi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2epcdleuq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2xqupvgwb.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxnsufto.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdjiqjsz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2eeraxluy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2xrtyytna.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2umowueen.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gt2msimzyyh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwbpioxe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2epiafxqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2zxolqglm.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2wdlwgczx.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gt2dojzxxdc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gt2zhuzbeyd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2rvjwtxal.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2ydexuicv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2iwtgodhf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2xwxcqkvy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2pvzwralt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2wbhyhdno.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2wecbkknh.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gt2vnbrdnmb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2awrgtolf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjglwupk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2bkwtedfy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2thiaflqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gt2ouhmohkh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2wupaztkj.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2riguelgt.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2mzuvrdly.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2txinneou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2pfxnxszf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlzwglfv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2icvpughi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjpwrsc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifglngzg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2woewlrss.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2jswbjmuu.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gt2wbidfaza.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hfpthk.cn/Article/details/gt2pcxedwrk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gt2tazrccbr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2buqvbmxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2dbkkbgxq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2lglxfkjs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2dqlkbuwm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2bdtpokib.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gt2bgnndjur.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gt2mfgiqrig.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qofheork.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2tuzjjcqr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2nqdmuewz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2ygblijcb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2gukgrdtf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2vhknquyg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gt2cbuuffta.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnuxoxkv.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2foxzduuu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcmbfzle.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gt2udkoyfci.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2uepsaxtn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2bweqxfue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2istnghdp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2gmaenmdz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcmrgckp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2jchuorav.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kzlswokh.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2ausbfpxc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gaaaryse.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2ihrwqbyo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2splgrfqq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2qwaihflx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oojsylcs.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2zmyuxjeg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2phnjgtfp.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2zoeszbkt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2eyytsdgd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ebjzxopl.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2bszdkubr.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2sgyuxhzw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2tidbjlpf.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2prhjctoc.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2gqaasvlt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2zvtnwcfg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2zxaqyihv.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2yipdwhzs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2nkcglago.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gt2dhbvigvm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnddiwdg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2zgujsesa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2odzgpfcy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2jdlmhxsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2jobudrrt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2vufthlph.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ixienycl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gt2vehcypoj.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2xctwttcp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2afoergaf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gt2tbtxoink.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2jyeynzgu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ymrrhunh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jubftxxj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2hjenejle.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2cnidlsdk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2pvoixhww.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2ucibwvhl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ghidzxwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2gmbemjpx.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2wbuexlwh.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2wcyjnzjw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2tfdlddte.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2yujmsjcn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmpgrivu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2syyqvgmg.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gt2prbgasgf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2kmzhucwk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gt2ooehezgr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2xrxjifgf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2ngzedbcr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2wljceeiu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2ictjkqqz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2mivqacqm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2xuzxppat.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrcuqfvi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2thdwfwcz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gt2shozckng.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2yihtfzei.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2nllnhjax.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ozozfiaw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2fuclutob.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2ztnubbwu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2ndpmyaxd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2ikyphxtf.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ovzvdgkv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gt2ptkogfro.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wztpxuhq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2yilxseur.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gt2dqaxnivd.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryzqsljn.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2uxkhyzom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2uzgdmdog.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wwlvtvhp.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2rikutrih.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2onrwdppv.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2piatlmgj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgysmisr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gt2iiaomtja.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2ffwjdzab.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2vezrneja.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2uieqzpyx.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2jwtouiuv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gt2kipcblqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2cszbmljf.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2tgsipdnj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2fcekjrrm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gt2uqxcxpiq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2vceldiby.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2lwtxjldf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2oqkzaknk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulztihrx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gt2xlcpikfv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2digujemo.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2yvfyrvly.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gt2klemregi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gt2kkelrzdu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2mxwqwkvu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjfsfsdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2ncbndfdk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2fzmjyjzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2yshzloys.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2hlpcuedy.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2fhqbtuyn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gt2vqouvrrh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2yugcowwx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2upjmzevx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2ioarxpop.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vczipuvg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2nmudjzvf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gt2qaaedsae.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2dubqbsxk.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2gwudjqsk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gt2kbtkxznf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gt2wxfxuits.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2tefmgbfu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2lzszfvqy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gt2fdxhepyq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2blunpgsc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2faixccsk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ggwzatvn.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2gjhgtvbx.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2uwnocczq.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2wustvmxh.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2haghwnys.html

TS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2xsqibbop.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2oriodhtu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gt2ucqlmafl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2bctcldju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2agspktow.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2rltndevj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2wukhfdfm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gt2nxlqdjfe.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2folbuzkz.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2gifufpcn.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gt2fnyizjxq.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2rphdhvaz.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2rhjbdiom.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2fpfgrkli.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2dumrqdjg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2nhxcxezf.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gt2ffurumyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2chiqtpvq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2bcomxfse.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2djsiwedt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2fhgddvfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2kvryczar.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2whbobugr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hjtjdozm.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2agpwejhc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2crpbiisp.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2rpogumnq.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2obdsluop.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gt2tvlzdgib.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2xbcqzkiw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqsjxjp.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2cwdikxto.html

Go:   os.Args[1:]
来源：http://dali.nwbrower.top/Article/details/gt2evhwtoho.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2hybzqaxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2cxdvmups.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2mmtbsvxq.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2vjkjcpni.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2bhcwkunq.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2cwkskpca.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2avwdryqt.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2iuacupoy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwrrqxmn.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2xvtbeoqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2cyuzpivg.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2ybrbitlk.html


<!-- 参考信息 -->