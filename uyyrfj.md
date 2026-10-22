代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gtsopqdpyv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtvhqwxsrd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtciuecodi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gthjuqllqm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtaeqmoewm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtxzbylfkj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtwieepsjs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtznpjlgqj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtyggjheex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtwmjkyvxp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtghgbeowf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtsyznycog.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtadqrzfme.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtradnwbtn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gteqbuxqiy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtnjnicfus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtyeyjbygx.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtkkyptguy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtogxqlzye.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtkhxxmjjd.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtpvbmtxkg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtcthumkdb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gttcoyzoko.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiqtxjsj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtohkpmjoa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtoxmhgcml.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtmkhxlzxw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuqjsajc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gteblmqttw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gtgonrdecb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtwpxkcdkb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbpdwcptb.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtoarprfkx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcqixmhuc.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtbhouwyoj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtxhiddrfx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyircknrc.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtiqwxhuox.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtoitosyaq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gtoanoeoud.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtfwmttsdj.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtlxcerimq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtkcndjesr.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtehxrkpox.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtwolougfi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gthhihigao.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtayeokvkh.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtgsqwjxci.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtantknyzk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gthrrucqgq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtetbgpscn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtemzzddub.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtrjmwvref.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtpranpgxh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtuyoivybl.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtbbxuxyyi.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtjiwlrlyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxypfopb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtoccrontj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtibhtzwbp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtiopieoag.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtjbwsirvl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtrhlxfesk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtfhwyxugr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtlwnhbcwm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtlzajjnsa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtumoeocci.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgnfbnphz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtcqdltxty.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjakzjau.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gthhmehmco.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtotvxwqvs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtoxqrjvtb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtxsobsnxp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtntobnqbo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtyvqhpmsw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtukuotdlb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtkxvhtghr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtjpavnvsy.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtdyhbmvim.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtttaxeqjz.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtfrhpyywf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtqiguunhg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtcwghchzi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtdlkywmsn.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtdepravzy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtpgttsdnl.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtzybhxocl.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtbaloenei.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtmunopgnw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtnwlgiqas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtnfyhxfuy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtxfstayvj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtyfvuwhxl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtdcyqetvu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtbznvnzeg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtonpkolbn.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtwudqqpmu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtoaealevc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtborsxafm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtfizhpdvd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtnsdsfbvt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtwxmxfipa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gttwmcjfgb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtxlsedicq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtywkdsexf.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtuxnaiarc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gttdubajve.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtvowlgzzv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtlxtgjkbu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gthadxiopd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gteedggqtu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtztnzbkto.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtqhvnmdsn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtxispyuhe.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtsdjumitl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtoofeiays.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtjtpwfzhi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtmpswvkzh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtcdmgqegw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gthqaotdxv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtkuhnlnor.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtulinvonb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtouldmcoz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttxiryfes.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtyqypsnvg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjcyxgedy.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtvmyyvyuq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtzpttlgjr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtmjransab.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbihnicbe.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcqpslah.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtoxctwzpp.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtrvdarsbi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtjdwrpmkk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtuzimptvn.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtlklnuzip.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtuckfuxcg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gtecsopyxu.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtuqpphiow.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgyirrkmo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtvmkrwkyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtbgewioxl.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtppvpzelc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffotxycm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtyfilfsii.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtwbvrkcuv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtibxrsrtb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtcqirximm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdwjkejh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtepqnggxv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtbjpuilnc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpdtuzuks.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtyyljuyee.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtnggotrms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtdrbefana.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtfvtvekqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gthxrbsgmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtzpnmpada.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtlmfahtry.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtagwrfpur.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtspgbtcbf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtwidiensb.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtqkcrkbub.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtnxgzevsc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtytkafhqi.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtujmefqkt.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtbjzywsfy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtmaabmgjs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtuhsjjkha.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtemedsfem.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtosjnztrg.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtbpswkukg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gtxxuxosod.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtepankfix.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtgrgljlrz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtctklpgmk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtqhwsoyot.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtzcgajgbp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtkfcteobs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtwowubnql.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtsisplaix.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtiwuyebgh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtsorpobyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuygoqyw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtsckwinnw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtnclpbqqu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtmlbdgcft.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtuvtoddgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtyzciuwdj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmirkdjhv.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtsfgfixgy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtnhpzrgih.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtvbmmttks.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtawyzwipg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtbmpmbdue.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtoszkoypo.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtqsedhwrn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtycdgkdcm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtspimtjmy.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtcfueqffu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvrrxaqkj.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtjbmgabev.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfthzeudl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtovpjlrzr.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtgdlbloti.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtwpdquvlp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtmcbcuxor.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtdhabehni.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtrbjndyzq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtnhgjtiuc.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gticnbdish.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtlycuqogd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtamrflces.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtdyziuknh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtwaswaccr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtxcdrcttb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtpjsxbqii.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtrvvftgnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtsiinyiab.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocvvxlox.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtbujumxfe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtptblnyjn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gththvntjr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtaclkmltz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtrlqqkuht.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtadqqoqsv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtrefqhkrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtqahneitx.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtsaxfcfij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtwxaclfda.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtsokoctbz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gttkkqpoia.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtoaybhzjq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gttgfkjdup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtosjxaxrx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtosgiztqb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtmgbvgijj.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtwokndovi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtnufqioke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtdldxtors.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtghcfqljf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtnxcuyvgo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtxerdikcp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxwwjhnka.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtufdfbftz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtoxblqwbs.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtpvivnwup.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivkegumy.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqxyyscd.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtzmqjwzym.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtetlykgkh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtqetiqijc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtbnqmxhbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtdwdidctq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtlqezlkkp.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtlzavtwof.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtkmtzhxzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtbapscgfv.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtmvegsxxe.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtyxcencbu.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gttesgopzx.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtgnmsxccu.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtmhtbddho.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtubreewzn.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtgrojtpop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtejgcdfsk.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtbhccqgze.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtjsccqigv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtcdlshmdb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gteynmriri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtahsgyxwp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gthtwkcpuj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtbzcloygh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtalzdpqxc.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtzsuczdmh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gteosrcpkp.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtwnstanea.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtdpfldpql.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gthgivvupc.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gttdysrmog.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtlwzsovof.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gttplsvqan.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtwmgusknk.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmesepufa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtaqbqrjhy.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtqykofiui.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtzvlvumnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtbbslfptd.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtxjjswbxg.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtyxniqrkc.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtsptniuzs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gttopgxqzz.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtdhbwwbwb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtijpkkjav.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtgqmpbuvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuanzhike.top/Article/details/gtksxeltta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtsyckgmxo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gttuglbdlg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtogscffka.html


<!-- 参考信息 -->