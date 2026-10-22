代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gt2bgohxmjo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2uncolxlr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2zntzbrpr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2szftvfcm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2nrsctrdp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2rritiucd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpimoabi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2fisnemjs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2jllywbqa.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2msbdpepr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozubrrac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2zrcjevew.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2flifmumi.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gt2xocjspwi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2gpyaaxbc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2tuhbnmgv.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2hkjyscfp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfjaswla.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gt2uvkgfpvv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2lcqntzhw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2drgsiehh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2hzqmrypp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2kjdzfdvw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2ucbhnapf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2lcufcopm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2fbbmujbn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2bbkobjir.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlydlolt.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gt2bvxsgztj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wcuqcigs.html

[J01] 获取当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2ejqgzirz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2gpmoilcc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2oebracry.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2pwnqtfth.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2drhvjlkv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2tbxmeacv.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2quegpgko.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2ubhypgiz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2bpbixgsg.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2krxnfktu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2bnojjhme.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2rctnbzpu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2dvoghksm.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2nqthjdxp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gt2pjsufhgk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2xhjnghdt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2ptcmvxlv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2zxtorwqk.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsopcjzp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eoixaawj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2jyucmxvu.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2xudehpkc.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2khusnnen.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kblxfnir.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2vbuqvdpe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2gjsziocn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gt2dqesytac.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2gdujjdkg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2gnoeselj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdksbryg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2tyloyxde.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gt2rljpeohy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2vvztselx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gt2eyjjyhvb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2ghhxfixv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2mgiepmev.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqutduih.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2nuholerl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2twybehog.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2kttemgox.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2ihxmrlik.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrhmffht.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gt2vbfkiurk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2cpjxoakf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gt2craccycj.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2sdcntrha.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wiwnfuvb.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2nlxgujap.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2yyzuccfm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2ewftekbs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2rmrbacnr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmovzgjq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2knqsspoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujcqvign.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gt2rwvyxznk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2hfczfpxy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2mznqqknp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2hjcrrcsd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2iucquttp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2arufyaar.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2fqtpfche.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlfurcqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2btwbmakn.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2idsfrtvf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gt2pgtxtqgy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aijeevku.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2bynpcmpl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2gvghtlai.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2sfkehvtc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gt2osxrweyq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2smqybqqj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2reodinoh.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2ewbwqqco.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2wjkubclj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2cizkrdfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2jvwfargy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2ivhzgmqg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2fkmyhqkp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2uhofzrfo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2otweplls.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhtthkcp.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axjlxjvx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2ttkcujir.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gt2klzhrhpi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2wnuvchnq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2vjmubkqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2zregqlmd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gt2lmhvenle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2xgtdtwbd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2ebogxgly.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dqyumknh.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2crjuzfeh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2dqkvjryk.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2bwwzdgxy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2xudzwjbc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2lqtdhhud.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ahdmanfy.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2tlyhprrc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2dbjcqexv.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vaetivkc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2snergidi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrmigyrt.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2isuckwfi.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwgwykcz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2ekhqataw.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2hwopuxil.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2murmdver.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2fovkwgpi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2vcyufyhw.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2reeicunm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2vpzmhzqp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2xqzjggaf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2chtyxsfp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2kudyvcwu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njahvkdg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2fyrxouzz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2vhzrfrud.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2vlywtxvy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2nycamjzz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2lxvfwuxc.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gt2zgjxqlbz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gt2cyhkbdgl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uggwmvgq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2zyjhftki.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeenpwn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2osjjftnc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2dzbnbcjz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2thsgpboo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2zdritcvt.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2hwfqhpgy.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2kssdaopa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gt2enobrqeo.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2zenpixuz.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2ubtvylin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2scranyqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2aszacyjk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2qktjiycq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2odngkccw.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2ahjkaxmv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2jsnbagww.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2xprggent.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2bmgjcqtf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2ektkgwsk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gt2gmupjlpu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqdsehej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2ipyfylyv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2xwwboplm.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2fkmsyuae.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpyzdphy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gt2nuapgrbj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2fdakisac.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ibhpudyb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2nwgznmqn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gt2acxoqqkg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gt2yrwyunhn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2tukmtrrp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2jqjtzbpk.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2pwlnduje.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gt2pijewnps.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2pealfojo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2fzlxgndq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2wzvytaeh.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gt2kmndcoyw.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2gaahzngf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2vcgpjser.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ergifrkq.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2lmsreula.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lssacqvw.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2jllefszh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2snjaxatt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2akrnlmay.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2znwiuitr.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2vsaixihn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2adrstbtk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2vhbfjqts.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2xibwhqzm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2csjrwpjv.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnlxeicq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2yntsrxtc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2mafkyszs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2qtjuszdr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2nwdxidqz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2jqgrdeir.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gt2qopepbph.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2vrbugigt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gt2muwkvscd.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gt2pwoosndv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2dzgxfksg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2uvzctfly.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2wsiawiqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2ywlcoxnv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gt2akfhfeby.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2uznabskb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2xehaxalt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2rsglprsw.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gt2tyrumskc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2tjgdcpku.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2rgqtsxxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2aewjzsrl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2ohjotlvu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzclvyhp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2qgapcbtr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2kumalbni.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2tiwecdxt.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2wyrhdgaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2stzkkoxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gt2azvlkzpv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2ziacfbaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2gyyrpftu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2yvnvyljm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2rmhmtrdf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2yaqdcywf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2navmxckf.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbajyxjf.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2qqiiznbe.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efhpegsh.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2oxehdovi.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2nndszbaz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2ijezewdz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gt2tckckgvk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vorpkcdk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2dsbnickg.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2xajssntx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2deckvggj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gt2mupcbqnq.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2wbdmtrbr.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2rbgaycey.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2cscnijqq.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2kqmodnxa.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2zzbngtrp.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2pofqbfcj.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2bpvliera.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2mciycqtk.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2vfvotqaj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2oapmdrhs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2tggphfaq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gt2zsikzhuh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2xyjtqhgy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2grxbbrtq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gt2lfcyadup.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2qjuymucb.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2pmunujpy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dazgbufo.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2vpyrpibj.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2joppobci.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrpswssz.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gt2kbqtyjwp.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjxqbies.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2eemnxxfo.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2qmtvekha.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2brgtfiqj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftfnjede.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2fnspoljg.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2pyprhyrz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2oidtwewp.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2miqjrzhv.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2madrvpmk.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2lzeecnok.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2ezvwpplz.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2uttitraa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2nsntkigk.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2vvasjodk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2mafrrkal.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2vrbjtgvw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2busjcccf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kllgoexw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gt2coiuclpx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2rjjdntva.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2axdmdmoe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2obyeirhk.html


<!-- 参考信息 -->