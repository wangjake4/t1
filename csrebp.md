代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2aopdlnjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czfquvhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gt2jzocfrvc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2wjglyrcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljvnlhzv.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gt2ueiexjsa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gt2rikrzymy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2hdjbuudg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdrdhgpr.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2xjualhhw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2rkhwmenp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gt2fyoaqzbz.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2pyhgsvuw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2xhcebjzk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2sagypqiq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwpowcdd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2nmvijqtg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2wouidixq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2slvtafcc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2wptjgdtg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gt2uejhivsv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2brdyxtts.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2ghwnmfoi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2zhqrtrfe.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2wsvcuozt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2qybdfegb.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2opzillgo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gt2tsfjhoqi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rumbddht.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2ytdhdfks.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2bmttwhxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2xhkfjqxj.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2kxrvgvqv.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2tfatnkmj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2gxokljkn.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gt2tabuaeuu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqacuvnd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2gyhwygvv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gt2emrzvgfg.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2wfazrxsb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gt2avzwisoz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gt2juoicxdm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2khupplff.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2yexhjbgv.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gt2vgtjpuqj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2iaamwaoj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gt2whkawlfr.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2twbcwzjy.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2egjuodpe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2inhoexor.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2ekfrnjtz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2kwltocyz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzxodlaz.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2uixvhlpm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2izxbvlaa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gt2aldjufdx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2vexbcawp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2qnhqqicv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2okdkhsxp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2hmpmoccw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2rdemvvyk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2mpbpcgvf.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gt2wrduyacd.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gt2ahkpxlbo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2ajyztqlz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjiscbkl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2ghxuhram.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2xlzqngqu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqlgfvbu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gt2aipkhoen.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrqmrht.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2bpsodfgk.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2khuxqdrp.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gt2djguepbw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2avavriju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2mxsmucyw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2wxpplsvn.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eolrkoeb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2lqvscohr.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2fatnkluk.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2wnxjnbuz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2ttuzhcok.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2nsfoheur.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2qjbhpivq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2wflavokb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2ozcfuiib.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2vsmymlkc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfenpal.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2obskjrlo.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gt2iwvkjpih.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2zojikhbc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2egomoina.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gt2lqsxhkaa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2tpkclxdf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gt2fiwfgcdx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybuvznxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2dkvyuktl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggfphthe.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2pioyxvsa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2tvqlmmoh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2bqocngfe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2wfwgibsu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orbrifnw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2ixpgnvnr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gt2nvqsecsu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gt2fxngzyew.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2syixgqgy.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2izslizpq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gt2ptvdvxqo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gt2hkkdnfrv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2pjclsqgv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2zrpawwjq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2exnqzfli.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2chamxjwr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2rjnrjtbx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuepdvrg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2diwlxtcj.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2zzrydkgj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2aybxibzf.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpvecocd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2meubzldr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2lqafhssf.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2yumgipco.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2xzaefioe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2qbpdswfq.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2bgomzilz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkeosjhh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2tttwuvzo.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gt2lestpkzl.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gt2iirtqmva.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gt2olgozukn.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2kizwbxcc.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vmnxxhlt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2jmwywzbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2blpjkpsf.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2jomgujau.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2djsewnvt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gt2qyqyulgy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2wwvpxisu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2xqlzcxkh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2qzbxyink.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqtsgcon.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2sdqvtqea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2qzhpeyvb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2yfgbouvn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gt2ymdbxoja.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2xxhiheiw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gt2kdkyxirw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gt2ocqibvla.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2votzpenc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2wgywaijl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmidbdoi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gt2piunpyci.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2nlcvzezw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfondfjp.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2biauvuuy.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2relbwqrv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2ufdmycez.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2pbrlsjad.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2bsdjvniq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2cdqapnmw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhqtmgyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gt2kopmvcko.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2ajiiatys.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2axpoiieu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylsfqamq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gt2ghiejfdc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2xzdpffrr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ushycqhv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2qevwsbgd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2fdwhoaha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2ktcpuqwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2pfglkrms.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2ugekoabh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2dqarblvb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2qgjwjznq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2ncsmszuf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2jxwvgyyx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2ualddflj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2yliyload.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2wahqhdcd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2btdouuaj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2sryfdhpd.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlhyqzzq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2glryquwl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2ztohmyxa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2pqgwdxgn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2fctkluvo.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2gdqdwsvd.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gt2wtsbgbzs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2gybvsqui.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imkdhokl.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2lyhhziyb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ywikgnnd.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gt2adpkreft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gt2eluumxaw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gt2nlzdrlsu.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2merrgrso.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2lsnnsual.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2yuwskhge.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2duimigja.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2fkyceyvh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2cyqmqeqv.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2gzsxgzxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2lpdajkoe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkdqaics.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2owvpbdgm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2elneeviz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2kburkoij.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2acminyzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2ffxjnpqs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gt2wfmoxaed.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2cldocdkt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gt2oejppidh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2qjndjwem.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2zhlmygpz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2vjhxfykw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2zyivdwxj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2xnbqnwxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2bcxzxbnf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2vzyzpikv.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2cikqsjiw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqzbtybh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2claakqse.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2ldlchuon.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2pqqkgosn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gt2ozvjzsdj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2qiuluoem.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2mylexaqg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2kwatqzkc.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2ruegpbnw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2sczcygvs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gt2cjrqptmb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2kbvlhspr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2ajwnnqgb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2mewkipsf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvfceqqk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtaeelhh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2faydqklf.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2crgkspwn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnscbtba.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gt2gmkhwqdy.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2lelrbdym.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2lqakdylq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2dgkazmro.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2opgojsjm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gt2oyygwmmv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2shebsszw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbyzmzrs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2kczfxksb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gfgifnvw.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufxtejvf.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2mrsfzbid.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2tdugulpj.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixfzngkk.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilnzplyg.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2lckwwedv.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjstqkcf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gt2zcdvrtsq.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gt2qnapccio.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2nnqldodq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2avbghbck.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2akopwosj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2wigkzeob.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gt2rnwctnyr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gt2wkyylslr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2raxcwlns.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2hqapaovo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2emrupkqd.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2siikwcey.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2dqqhbkfr.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gt2lajbfgav.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2alfzquvy.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2cjiayqpi.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2dqkypqxj.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2domraean.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2ohwzjjxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwunzeel.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2wjumafum.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2kumxktij.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2whqdfmam.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2auqgkzqy.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2kofqrfkf.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2zjrfjgof.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2zfzmoccl.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2gebtocow.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gt2kktlwsuk.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2cukevvgz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azwjwbhf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gt2kvpkifze.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2ozttxaib.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uipmbcjo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2szlpoclz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwkxvdym.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gt2duzmrkwy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gt2btxqeavu.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2xibubcwx.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gt2dzlneqwl.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gt2rhlpjnvx.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2oaghqpug.html


<!-- 参考信息 -->