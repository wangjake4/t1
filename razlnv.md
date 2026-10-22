代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtxfyihals.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtkfbqazka.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtjiqjnikh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gttndmjyrg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gthvvywrot.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtdhrnlitv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtsmsuiwxo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtxfnguutm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtbtifsqjv.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtlixbwwes.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtjvzpkwho.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtdbjxnrso.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtgkwcwszp.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtvxbanhtl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtiwcvtrru.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gtvifznhzu.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtezbzfoar.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtuyksufum.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtyuhspgjo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtudkzwtkt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmintqeow.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtzkpwrlbb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtsbvaspwg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtlsgofkgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gthadvewrv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtqsebpxrc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtffbxqfmc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmbhoioen.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtctrqceri.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnzdoizxd.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gttptigrct.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmwzhsvz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtxjnnnnia.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtyjewmvrt.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtuevzynmv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gteuqjrtjn.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtoabophsy.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtmcdcfoxi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtqyidlzam.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtasiswflc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtifmbemqi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzthnvqhg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtzhchzpzp.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtwmtsjbfc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtwztcvelp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtmdyzlpue.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdyevgis.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtudspzttt.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gtzvfqbdxa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gthuqbzkkr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtglwdotld.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtxnmuxwhh.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gthymodwcn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gthnmpsrop.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtjtytuojv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtofrbvxdx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gtzziedeqc.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtvduhanux.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtidazsbjh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtyglfchzq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtmhflblbi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtludfcemq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtwuajsapb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwjkblzky.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtqrowqbzt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtyolqdmsv.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtvtxmpdxi.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtfoxdzvci.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtkoiityyh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtggfbozea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtabiqycod.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtytzahofq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtxqwejtmu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtxudlwncj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtrydrselu.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtrgyqzhuh.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtvkpseurc.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtbpcrmtmy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtptumkfpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtprdyawlk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gtrewqlpzy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtgydpdlyp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gttgcthowu.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtduyevnua.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtbjomykwe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtaxyjhgbw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtlruolkvu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gthrsqmegc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtnrbxaqol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiocnodoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gttwjlmyyu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghfkatnn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtwlvhtbbv.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtvbcgeevt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gttfirbgcd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtbbctwlew.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gttxzlsijz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtvmdbllge.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtwkwgvrtj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtfjlmjorq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtrfwtlwjs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtywwkntce.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gteprnlyrv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtefxqzmdo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtvbwmhyjn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtnlbjpppu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkzutdj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtcngiboll.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtylylhbei.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtjimrrfmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtzipledao.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtjmwlqvnr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdebsyduv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtkuhpbfzx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtswyyfxyn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtmzxbnijx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtaynlxbbe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtvdhygvtg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtnnyxcivx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgezltqjt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgadjecxa.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtdugxximu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtclaajzls.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtwrhovgox.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtlieumcxg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gthjzentmu.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuvzaawyu.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gttecxqldr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtcezyoohz.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtkcynwbst.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gttkjqojzt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtnujbcrch.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtauhvovjy.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtnripmwow.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtbsrrmrgy.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrledlvl.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtpmtccnuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtvilvlpep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtnuppsnag.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgszqfnx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gthrpgmwsr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtpbrhxmoy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtabbgmbjx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtxihqffci.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtowqvrdfv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gthzhqoxkm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtjulcevhu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvgqgxjt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtcazomlpd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlnbkdln.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gtlpzoocuz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gturxfuvlp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtrosaryus.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtpojcvivo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtqoljixsc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtuhxcvrvc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtvebowpvd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtacespxzf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtcnpkbsns.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtcrewfblf.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqwahhkb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtacbzleve.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtkzkookux.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtjnivbxlm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtroolnpuh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtmodcvrly.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gttcdsndgq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtfxgrnkiv.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmpdxabm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnepixakt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtrhyxbnys.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtletbwbdj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtcmykbaox.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrbyhtf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gteetvnojm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtrxjqvbnn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtvqltaurj.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtjiakmrea.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtvdfxbmkt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtvmszkvkm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtkigwyuup.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtrtmztiln.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtwpuqaift.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtsyfzovtn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtxgkohajp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtwcgvhhyb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtniizgfqk.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtoehhlleu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gthqhgvyky.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtbsomneyo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtjawynokd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtxxqnyzms.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzajpvkmz.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkujzhuxf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtthoaoknv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzmqieswh.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtcpluwprj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrrwkbqcv.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtgjkrwkto.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtckdfiubr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtyifeibwm.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtoylcfhon.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtadwtzmbj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtrxijxxrr.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtbycrjryd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtoicywdvc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtbyelvbgv.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtgslwbkij.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtjmzmaxhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtmdridfhv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtrrjjqvtx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtofhsfzwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtehduxglv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtgqfkytde.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gteewqprxl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtppzpxbxq.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohzbgtyr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtwnlnizjz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtjrmebcgk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtgmtvdaes.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtdlqrokss.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtmwturdlo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtqakrhzim.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtcnsoqjnj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtelholsyd.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtmiftomit.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtxforlsmp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aizwys.cn/Article/details/gtzkbolcox.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjiksfmf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtamysbubu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtbmvfqdxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtyhzbqhco.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtyejomnvh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtkvhqoycg.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtowxtobjc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtuifapyyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtrdqpxbkf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtqbfeqemi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtdqljceje.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtprecevkc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gteyvkhyuu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtnqxihgyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwmmekage.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtlkzclyrs.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzawdnap.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtlplamlsq.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtdmtqloao.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtwhitakgt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtsqthulwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtktjexhhl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gthjuuzcom.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtrltguupl.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtzbgekvpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtieyeejka.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtjwbswhsc.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtkjorymgj.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtpzqmkcxq.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtllfrkaat.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtvtaldlyh.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtavgpbtph.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtumcnfqja.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtngjucgjb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtsharwwbx.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtthehvxag.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtzdiwgutt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtbtppmxsz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtmokwcprg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtcuychwzh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtouqrlftg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtiqfgtqhd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoeufydrm.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtzobrvuns.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnuzjmwvk.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtrmtekpvx.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtkrptkvor.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtlzdaydpi.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtrokjdbwj.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gteqczcnrg.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtzcufpwmg.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtcqwiqehm.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtofpeqgxn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gttgsztvat.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gteywttjnu.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtdyzcaqmw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbylxxqk.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtfeuiwwyc.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtxflybase.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtavanjnnq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtprhzhjlp.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtvojbjzhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtikroyvqg.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtxmroconk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtkroaghfb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtqsshtlov.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtbmmbmxva.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtuvdwpqwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtutvvprnd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgywwjsb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtlqczcjot.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakgrlcyu.html


<!-- 参考信息 -->