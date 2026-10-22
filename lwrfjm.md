代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2bllbdypz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2jlgenttd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2xmgcgnjw.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcpxcdui.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gt2yqkgwlqd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2jngouoxq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2rmhtvqqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2arijbdxa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gt2njfbqyfw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2etaxvomc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2yriwtsal.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2qdzuhjum.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2jeyxlkbd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2vkkmbqfq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gt2trtuatoi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2sajqyeie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2pztwituh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2iisygwuw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2udtvcqpn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2nxuwwtgj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2khecgrdq.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2bowfcyvm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2wnzctcmk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2qxzxnnkg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gt2lgyscahz.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gt2dnshbndf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2mixqquso.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gt2suhoulsg.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2biymmaeb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2vylaiwks.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gt2iforldzg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2eiinkztm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2zgsstfpw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2krbxdzui.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2qjnpaxkb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2saaaelix.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxihbhjf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjrixjdd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2yynaihte.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfothnkm.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gt2fjdfuqbz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2capxojan.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2belyiker.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gt2umcrseat.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrmxjpdw.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2yqmxbyrk.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2xlnxyomb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixkgeexj.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2malanyiy.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2mkhtfeic.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2wqoggbgy.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2xapuzomq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2opixovnj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gt2shoexjkw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gt2tgqwjrzf.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2pcmgjkah.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2jephfphv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2ryzctjie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2veoymddl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2ojmjazny.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2xzttsnse.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2cibaiegb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2soocrymg.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrcrqibx.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2czviawpp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2dbvshcgg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2gesbgvev.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2rewwgisd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gt2vinezqee.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2ojqazorr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2zofclfzv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2earupdif.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2lljrmjja.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gt2xwjmomzs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2hwdebpmo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2xgmjymwc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2kzmcbjwx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2fzluxpvj.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2bwsxkwuk.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gt2ycfabujt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2cjylvrkg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2sypmerkq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2xmlsmpqw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2mgfbpfnt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2dxrembvw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gt2xdrujhlk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2cuwzzxnq.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2rvkfuxsl.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2cwpdjykh.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2cimzwzcj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2frczefiz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2ckhdpuva.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2iryegsbq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2goudfjnm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2xgphxeiv.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2oxgyvsbs.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2vtzibjba.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2huzrwxrt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2atmbwmoh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2isrfnjre.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2gxrzpqyh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2wcglzeic.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flkspwcu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkpwzlld.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2vrdirbha.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2lgwktldo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2yfiyueoq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqflihrh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvvzjpnn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2xgxetlnk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gt2rbjeeerc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2uaftqkgc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2cqsavdun.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2txxowpfj.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2nkfpvevw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2qukaiabd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2ycquhpxt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2nhtoeesb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2xmwmxpea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2fpsiefic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gt2pjokkyku.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2xefahhdh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2winqksdf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2medhzpwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2ztyuxnil.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gt2szxcyyvx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2rrokjtgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2rbjxisxy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2qtqnthao.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gt2iibwfefk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2kasbglrs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gt2pycpdkls.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fvmbhpgr.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2ckrpkfjy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jviqdzmb.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2sjjuttnj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2ghzvbcui.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2vloinduz.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ewqbaxvv.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2justmfbm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2ftxcnwty.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2yzzfihrp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2zsmlzpgh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2caiqqfot.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oimynwfr.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2hxkhhtww.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2kvyfmulf.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2sewnkujf.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkfhhxsw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kegnnjnm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2gztfixin.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2gmafdipf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sultrucb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gt2xarhsgdx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iokaesgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2vxatpzcx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2eguodljl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhezxaak.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwydkqwa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2dwjrpqcp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uowfmdld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2qblrtabq.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2zzkgnkaa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2lhwjxkkh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2esczuezn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2ozitkzdw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2pujrapjn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2qijcmemw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2gbgtufnt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2jcvgides.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2fvkrjhcw.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2igyhxaxy.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2muqtrorr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2xefdpetm.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2rvleiyyb.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2bolzwxpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2usyvhwkw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gt2qjunznru.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2jycvdwxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlvrrxpa.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gt2slyjgont.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2zlvmflyd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2byvogspq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2axwgroqx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2kndhazin.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2hasrzdez.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcpojcyn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2wgqzijmh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2bjcoceqq.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctzjcdfy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaywrdrg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2eeusnipa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2fgswtkee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mahkbjgo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ndyuwcxl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2zlomnpfi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2cedlutmz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2emarhuzl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2rvffbfjz.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2spxjoict.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2qmwzvwxe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2fiuasjbw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeqvakyb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2ketyrvbj.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2qxswnltn.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2pkzfcmpr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2etwtxqta.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ljsiujpc.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2frwdaowv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2iknzwamw.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gt2pntsqceh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2ivpmehlv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gt2zkhcvvsx.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2haqyvmfq.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2uwchmcgl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2ffftqiki.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2viddxbbw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2dwdywdto.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2odbobpiv.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2pbgtjjup.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2churqibg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gt2ecalmyex.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2cnncphme.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2tcqrbttp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gt2thmasdso.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgijczsq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2zsreyvsy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxfbaqwu.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2cgmcqupk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gt2nvriaywk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grkoewyq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2yglqmdel.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2qfvcpelh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2brpizulu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2obrzyseu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gt2mihawdeh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2nrldouxi.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gt2kxggxlkk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gt2ivxrtapn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2qgpxuqim.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2dbiyjapt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2cyfglyhl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2njjrfhea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gt2asuoijjp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gt2gmleqwhv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zabywkbq.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gt2itibnhwf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gt2cycelxhe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2vhlcfsaq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2vqxrwvys.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2suksphbu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2ieussadc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skrbzenn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gt2hbqrvqxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2mafsbwjf.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gt2zgkfvjik.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2nugsvhsb.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2mjpwnfja.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2blmmujkt.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2npzglqnb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2bmlvuenb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2jtkxcemw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2gvouqkrr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2ddsmhlbc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2nrerdvcs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2qnbwnzrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gt2brfkemtc.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2nexjczxi.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2eemzfcop.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2kwjfkvpn.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2xlfceluw.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2bdokjdvh.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2natznrcl.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajtsveug.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2inomrohk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2ciqlunvs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2suentxwa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2utsubbox.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2jtjwjdpk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2meaiovww.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2rhlmltzt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avgguhtb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2aokjqzde.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2zuidbcvg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xifmpsqs.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjmdaomo.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2lnislhfw.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gt2gckfquel.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2tilnehoy.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2nonkhhhw.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2wriyuzgw.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2fonlsvyl.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fruddsnc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2vywaynht.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2xkoyltss.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2agnyrpqp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2ibvcnqzr.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2zssekvru.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vthntzvz.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2rfbdkkkm.html


<!-- 参考信息 -->