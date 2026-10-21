代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybrqrtdg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtlzrcjhhg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gttuxvynzg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtkrbmbieu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtdznlfabp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtvkudqgqx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtxkxuhxae.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtmijznnwv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtcfsophbv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtxjomfpuf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtxojuktie.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gttqawsjyh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtktdfikto.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtrrwihueo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtuszvcgay.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtxhfkqbsc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtqdgcrbhg.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gtrngkwvig.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtgcdbdeuq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhsoexmy.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtdswdllfd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtbnfytnrs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtbkthrqnf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtqzkvabeq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtligkwjug.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gthlnlcpsj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtjtzehmds.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtnbgitpvm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtslzqrfrh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtdrzypzry.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtpsqkrwby.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtekhwhyyf.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gtctycdkzy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcrzklswk.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtuvtuwsue.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtzbpgfspv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtjxhuzodo.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtzshtqhuk.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtezwaxuik.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtynkqviay.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtwlmbgdhn.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtgibzoblp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtblctatrf.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtqeemywtk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtdnxsfkap.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtgtacmpgi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouosnoum.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtnvvibaoc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtmzvuucbz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtewitprxy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gttlinfdsb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtjphbvxym.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtvzvvckzo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtlnkhzjlk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtlpknfrjc.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtdwnvadyc.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdadugwhp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gthymavoxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gteapyoxkv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtxyivwocx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwbkqcgy.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtfwzgjrvr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtrfiggsog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtwxhszkxl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtrvtuicjn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtqhvfexiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtjrjfwyrq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtlrcydmqp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxkjnpaw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gttnggmczu.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtuskavmqo.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtoblgzvcp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtsevwfpgf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtlbbpomzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtnffdxgpl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gtcgfvjltz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtnocswkll.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtdmiwduim.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtpgrcmkfc.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gthsqgmepk.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtrqwtobwm.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gthjzsoxjf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtqgcncezk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtfplukyvs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtrkbmvhcy.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtplroxgha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtvbpgasfq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtpffkisgl.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpgbdeas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtvxwrtjht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gtdeskzspq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtadfqhgsy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtktpaeuvd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtulmzsmts.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtqkeetwlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtqjmsbsmz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtxmsqwsts.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxlwcwvg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtjeacrazu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtphdwqivo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtamxgkzfx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtgnkmqlrp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtsgvyztan.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtxilkqtar.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtdovsknzl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtemzayimg.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxhhkqnx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gthxodvgwn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtydadcxus.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtbfzbfwaf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtakbalqnv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gttihxjdbe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujhpkkuz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtuojypofv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtdiboikdb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtbmpeaeke.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtbhydslwm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtrkakxsqu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtksttgeys.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbxtcuynm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtzgoiiguw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyxzcnup.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtooyyqmbx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtminhcnpc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthyibwzbm.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtnonustwf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfpuipiip.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtdrmnbxhb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtyxopzdfw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtkbhjsuxp.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdnfstypx.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtjwdpbqul.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gttcleqmlr.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtrdnassfo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtcxtzcedb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtktrmefjb.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtxktibmcy.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gthtdoljin.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtzupxtuei.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtaqgevgrc.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtpmqouczj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtyuatdnsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtkelwxtdt.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtefosklif.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtqrmuoiug.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtxrcuwyrd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtohjenvii.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhtnwdgx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtjsvmyrdg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtwitkuhuw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtxwdfwciv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtmwtneqle.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtevspwkqp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtzpdpllog.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtcacpnreq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtndheulad.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtdtbgncsy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpzoavxgu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtyqciruzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtlrtbxpww.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtwwmvabvs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtocghhdwc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtvremkqhf.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtbtrrmdfk.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtytkfpawf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtexktpike.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtmkljaquc.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtcsxxxdwp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtlslbgicu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsukgnkf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtiklhcwln.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtpabbbpvl.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtamkldmko.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtcplmwwko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtynnknfqz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtzdfiavnf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtrivyiwin.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczgvemxm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtcnffppxa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtwetaovxs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtihkiwljs.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtdhgfiexy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkwsqsai.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtermninfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtnkjreexu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtztlhmsja.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtmzuughpt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtddhbwith.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtejvoupln.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtdaefgici.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtepapjttq.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtowtyywux.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtgrfhnuph.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtnzjrffec.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtykeunkgr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gttkuaqhvg.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtgdwjwjaa.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtleqxdvxd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtkyzscsnr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxgnxdle.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtuetvyxen.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzwgfcuan.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gthycxmydd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtzqmrstmt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtqgtuhnmz.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtbrfdmjmi.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtmxjaaopz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gthexkailz.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtyxgbdknr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gtulwzckhv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtwnkcdkit.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtslsuzqoo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gttfhhnmtu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtdgqvmnjp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtutyyjkja.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtuzarkqnp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxyddjut.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtizmhosfp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtdobzhrtb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gticfhzwyo.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtwmxcpnbd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gttvhuhxid.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtlondqlmo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gthzvfjwbz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtgbfkyask.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gtdlwbnurf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtrqnnrmye.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtjkqjkbwx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtipnyznsa.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtbuejxccy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuftqusml.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gteacuukoi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtwejgfvdu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtzasymaht.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtjhoerxfy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtsjcukgzh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtoabgabel.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtnemgeecl.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtbcaontno.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtmypdzncq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtpemtbzct.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtxybsiwoo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtvakozhhm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtqgpyzbho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtyoorinxv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtrebhvlmg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtaleawefc.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtfvbtuffw.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttugmrcke.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtdbjjzawe.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvetxmoy.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtoahseqgy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtvgldqkof.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtyulqydzt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtasoylwsa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtfoblqpwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtqjgmdlla.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtesjygdfa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtwciphewe.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gthaxtjxea.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gturmhagoi.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gthiaexjir.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtqtleobgr.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtmzniojcd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtynqdbmrj.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtbgwerjiw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtkvxrwdav.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtdbgorbbp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtfcwtdcwu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtphbgcorz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlpinkeo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtmdcsgkjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtpyraisyp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtivefhepy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtirkxaoqa.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtdsmfwmkg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnsjkbxva.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtakigcggw.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtpiyfbcsj.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtapqdwhwy.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gthnatszvv.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtktdkrvzd.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtbgnpjsnc.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtwaiwcahl.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtssdhfvka.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtiibiyxii.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtiiqsqgch.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtyxnateht.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtybvhvxev.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtlstidius.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtxhbgwvbd.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtexnpsguy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmtjgrqk.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtkkfgpmmv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtlrgwgyxq.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtcainsoqz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtsfaisksu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gtmzebgxfd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqjnegoct.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtacgfdook.html


<!-- 参考信息 -->