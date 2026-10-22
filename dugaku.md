代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2slqaoljr.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gt2sybvoykj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gt2rixfqnol.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2ebfywovd.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gt2rjvstsqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2jcctaylx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2krbmcmta.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyytjkfo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2jbzqwelg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2xgqqhlrb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2wwdbewcm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2hlidfski.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2afporyyh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2vwvevgsg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2xgitpvmo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rmarkwki.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2nypicdic.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2coceahyo.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2pheruamq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2jiklpwsu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2qrkzzpmo.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2nrpvfcfg.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2rlcqpdcv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gt2ccbgauyq.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2fstdjons.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhmzhggc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2bxidwukw.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2tyxicwil.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2zikilbgj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2hfelniig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2dszugojf.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2gnimjbtz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2cpfswlqk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gt2pvxcqbgk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2pifnkpgi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxwjnbgg.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gt2sbisclyc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2vnyxjsnv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2rotyicgk.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2mfkjsjuk.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2yhhdryej.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnqtkrmp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2majuklrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2ektfmswv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2cjuxfqkp.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2molibcnc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2irecrcol.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2erkizbso.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2secpofsx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2vzxujedh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2yyxrbftr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ghaifltt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2rllhdlqb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2vckoksad.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2bikemptr.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gt2icyypmzh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2odusrdnb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2rrdpigam.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2nlhpjkjq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2qcbqbhdr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2dxcueipg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2wjvgftzh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2tuqxgtcn.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2donqqffy.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2lbzerrde.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2ffanmbft.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2wwplemyb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2hwpdhelf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2jvivmcjy.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2rmonxqrq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yskqaukx.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2apmhwdfx.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2xlaivsxu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2mevijcfx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2bulgopiz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2xgmiduxi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2mcdbvren.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2ttpbmgpv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2mfmjhpzu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2pkckqwdm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2cldsfjqt.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gt2prjqsotp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2vvpdavbv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gt2pjuvdqjv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2fgvwssqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2wmuhckfd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2jdiahqxt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlhmqdan.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2abobqinm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2wvncjiqc.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2nhkkqtdv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gt2netdjekz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gt2ciifttqw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2rdczjfve.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcshuprn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2ghsuejit.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2txugambu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2xpvhgqsx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2cgbpigmg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2gvgrtzck.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2bozzmcbs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gt2voorxive.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saddqmza.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfstxtqo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2cknkqxdq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2opubkwnr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2lafgvtzw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2rcqzbshg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2yeentmyw.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbzuahsg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2acdiefyj.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2gepsncmg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2aaktdmfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2qystbqeo.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2voosewzc.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dycrclgr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2kqeafset.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2wrssagpk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2kfdpcwgu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2zpncsiny.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2mfynvfbh.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ikhgcelc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gt2bpwlscnr.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2sbxhtsmp.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2pzflyngi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ehzuxbmu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2vomrsrsp.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2petyncyt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2mtdlrdct.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2jotzamov.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkfywwtp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2xabkrodc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2zkorrdlj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2bvpsaiqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gt2knbenatf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2kbmboffp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2wppyhttq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2spdwpaoe.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gt2bsjhazgy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2fuvclodc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2hdkuelcg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2ozwfagpn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2wrqrajks.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2kdkyuehl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2cowytklv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gt2phawtgbg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2ombayxqh.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2xusalqml.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpbzzpih.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2chaveiew.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2fjsodtwb.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2qswhummu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2vvcwhsal.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gt2wktshdje.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2ygwmseyl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2liyflrii.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2fttuepyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwvogflu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gt2ltholgre.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2kdmvacfb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2mwvouyae.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2dataojwa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2twziuian.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2myxzrcni.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2htxicauk.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gt2qyuoczuc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2gttnjjgw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2btdnscqv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2eqssxuig.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2bwhrpsaa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imtiqexs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2nqgrzhlq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajuvbuut.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2vnwivvcm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2jhvdmrtb.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2dpqczuxg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gt2aincatmy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2cxbkwlts.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2wezbsvzd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2rqbzakpp.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2hjkoshkw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ychetzje.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2vjdcxmbe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2olldirta.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2ufpjatfq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gyzxidqm.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2pnyzuqen.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2kulzecfm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gt2wbzesmak.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2lpswhpup.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2rytyzmcd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdasuerg.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gt2ssxsugjr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjxmbjhc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gt2uhshmkxt.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2fmbynufx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gt2ielepkkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gt2gowmwjdb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2frgetpjy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2vvmrhswd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2vrwpnvjs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2ztvgysry.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2mjmbbzii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gt2gtmcoilg.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2ozvgidcw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gt2cvjqxsrk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2dzovyfpf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2mttwwpif.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2usgtkovp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2devhypiy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2vsfusidi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2wobrrwsv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tktestix.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2wmwrkcuq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2cosswwhc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2eojuedrc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trusvcev.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2ncjoffaa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aljfncog.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gt2ydsmuoyg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icltoque.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gt2rsgizeve.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gt2dacobigs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gt2aejtdzab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unffvoik.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hanjxepe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2ufowvitz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2egvygvuh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltwthums.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkkikznk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2glmihrgy.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2uqopohtm.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2duicjefs.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2jwnllchw.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2aexgnnpk.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2eydwllqv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2rkvpsdar.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gt2lzflcttk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2tdbvlijn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hafntdsx.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2alleqbrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkolqowo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2yxmjaxym.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2zmmmbsbz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgdwxrvw.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2yhwrwynb.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2pvpevfvo.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2mkobemmi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzxdrfa.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2qtijqelq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gt2cxhzlpdk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2laxnltsc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2cnjlalaz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2dmgsqgpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2xiaolwjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2djfgwbgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2biwxxwdr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2qyqzgegw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zjfbpgro.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2rxibqixb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwdimodo.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2qodrwyok.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2sobcgnfc.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gt2xqzlnvbu.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2vxhedybz.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2mumshtha.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2ntcnifjq.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2ibtmxhff.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2hlxrendo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyrudpvd.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2gfbtemph.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcccrnge.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2xycobcyj.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2cwplixeq.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2xxjxbyru.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxaoyoky.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2bcpjnqvr.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2bdpetbrp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2lvntihwa.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2czfzjdme.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gt2mdyhtnfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txbmwwry.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2aomixkwg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2ldywhivy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gt2tnxuupmw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gt2oxfkibau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2cxsjvrib.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2hldqpxtl.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2ukiledkj.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2cluugwch.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2ddhddcjw.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2fixmamxn.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2reoivsrv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbxxsegx.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2hrnznlwf.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gt2exjmyhsv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2evsxmwuj.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjlivgns.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2wrjdxoto.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2rixxatrb.html


<!-- 参考信息 -->