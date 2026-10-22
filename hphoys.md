代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2gsunzxjn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2igdtcbxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2zveivsro.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2cypdknha.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2ytkmsrkh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkrfupqb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2lirwwavx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ititiiex.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2nmchfrkc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2twozoiay.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2uqqytqub.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmrtgjje.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gt2awulfmhi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2jdujffmm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjajnvjc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2stnpkcby.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2fsyuaajp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2svzggbbx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gt2hkgtycfm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzdvudab.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2agmpkagw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gt2xavkbzna.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2tycjgtkd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2ojgpuygz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2clzxkkoa.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2luldgimc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgqrhboq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2nuvjtamm.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vouxtukf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2cbxstcfl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gt2ycacygze.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2dyqftplt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2tzwvyhui.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2zpyfsmhu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2tsvtgjwi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2yuunzpdx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gt2svrcsdqo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2jkbuvprk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2gjytxhup.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hfpqnolh.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gt2reqfoyis.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2emhmucfm.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2sngfhhao.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2tlmipuzn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2rieicvdv.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2sbnicnga.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2sisfbpte.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gt2xvjrvokd.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2ufunaful.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gt2jfdbhhrb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gt2wxehamku.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2sbxhttrv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2etiekewt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2qwwtoals.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gt2radbtejb.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2fngouzry.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2xuhnnkux.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2dedeeobu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2mcylespb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2taihofcl.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gt2kcsvvoaz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gt2cmjkmugy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gt2abwfjmkg.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2khzcwouj.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2gjsgluas.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gghnjhvp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2fuyftsuh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2hkgbdcvx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2uwnudkoq.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2deafotcw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2zemaupfm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2dzuxdfzm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2qfmtzlip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2yjknonfc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2gjakiniw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gt2oxizrxcq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2efqgxqoq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oneqzxiw.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2hophzkmh.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2lbeaycpr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gt2gcarszax.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkfgykhu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2mxbbcdgn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2ffjsqclb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2grkhjpuz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctahxhbu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2aovhtpng.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2wjrlsbff.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2aipleicv.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2yytpwquu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gt2twfiveca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awcftxuv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2ivmtfwxf.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2gbdihyzg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2offmkkcx.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2awvdyyso.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gt2qeipyeyp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2neyucboy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2trvyaexd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2gbabjeyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzgrrbwp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2wldjevwq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2covtlsjt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2vwmdhker.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2fpddlaav.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2urgufmka.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2wohqgiqc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2ljtfluwd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2escqakem.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2wgoobsay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2dcoaltix.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpnavtvw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2tjmhibny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gt2qjpfobwv.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzhdykrk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2xifolrjs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2jzfvsfbf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2tcxwyryp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2qmfvhdit.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2kzsnkmyl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2thrtwjtq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqlcxzsp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2wtqbzqbl.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gt2kqqbzqtp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2wswqdueh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2wdmbndog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2nlssuapo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2nbfhaqiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbuefved.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2xkcodioq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2jqsmgkit.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gt2cjlhzrli.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2fufwmref.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqwelmml.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdrcuyzl.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2vdsjrklk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2dspvnwon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2choloewl.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2jklxkupb.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2gzqvivya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhdryynx.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2iswqeyxb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2cxomeuzl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2upkxqtxg.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2bgibstuf.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2jevmkmme.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmeblsty.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2burknoce.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2qnlibdot.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2pjtekauj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2xefhkepg.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2bhsopxuq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2esuyycwg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjjeyewe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2jutkuxgp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifxlzvsx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hrsxgrro.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2eeclckic.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2tcodxhlg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2mozfacje.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gt2sbanlfmw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpwwlkup.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwesqxwj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2ikktorhc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2ndtzsbfr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esbbgrzy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgrutdeq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2dhgdsshp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2tzkyaytq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdieohet.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2eaznfdyc.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gt2twzmflww.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlheyuee.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2irylffqp.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2oihxuaje.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2oqimpoim.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2fojaedxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2rabgkeom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfqawn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2hzdugsxc.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2iagokefz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2umtefcio.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2rcjcewrw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2ztmvzbyc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2efasufmf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2qpkenfra.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2wvmljyes.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgdmqrqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxsppylv.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2gpznwnue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2cztzwger.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2wavsvxps.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2fzcrfklr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugjexsxm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2tshnxzae.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2anayqnop.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2okatsouj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2gfszvajs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2zspapuhn.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2demvflpu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2jnzrsxww.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2dbdenaxq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2jvjttxnv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2vhfdbadd.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2qiifelxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2kijhrqef.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2dsprqldm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2lwysbdkw.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gt2xxmctmsn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2dktbmhjg.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2ncppbqui.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2cietrrtd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gt2hacivpbs.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2apdppxbz.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2cigxpzky.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2xxowupqe.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2kofmtzpq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2frahemgp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2husxdugx.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2utttwgrf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2dwjxvczo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2ovosttyx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2blpdovca.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2ziizwdui.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2zernorpv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2sgbuzmro.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2asouzefq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2kejacctu.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzhpmgfu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2ubyftavm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2imjeoqgo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmexsykf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2oglxoyaa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2qbptfqrw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2ghfgjkfi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2uajqjdbw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2qgdimqho.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjiskoor.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2rzofkbgy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2rvynmdmf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2nspzhisp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2ayfahpkl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2hjhxkebx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2ptglakhh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gt2arrstkcf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2hiacgtyk.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gt2nkhunblx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gt2rvovqxzi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2xfpqnplw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2pkbrrday.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucsgctas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gt2zdxtdatb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gt2mmegxfla.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2ulvmphjo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2wsobebno.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2erknuhlx.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2zpthmlvx.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gt2rgxvyold.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2eauccyal.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2zdpxcpnx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2xfdmpnqp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2peaqntwy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2smyklhjx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osibmdiw.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxpxztfq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2wxhvmnku.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2tmtszlpe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2xepbgbsv.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzfdqtft.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2qdqbxmbl.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikyawqwe.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2qkhkxdow.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzifcrlr.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2ruraqsgd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2kbccrfpe.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzfnbpis.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2vxrghyeu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2plqsnooj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2lthftqiq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2gsfxforx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2vrwgzwbv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2isathriu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2sqmvqeqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2stkdquxd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2drhyhndb.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2fwipvztb.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2sbvvqcat.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2vsbmanyr.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2dvmessfb.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2prgdwzbx.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2zlimhdnu.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2hidvkgam.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2nzundicb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2muytslma.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrmhrnff.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2wragzzfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2xnbiqvkk.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2wxmufjwh.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2kgwdkubd.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2adbngufm.html


<!-- 参考信息 -->