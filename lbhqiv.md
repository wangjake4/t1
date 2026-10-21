代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtprjverbu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtmoxivhdz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtibsatwnc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtyuuvzsfa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtaxetwdhy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtsnbhgbqk.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsjntdgpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtuumhixnm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtabgglybb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtwixszmen.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtudlwgclt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gticabflsf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtklotbpzm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgixsstnt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gthdluxjxa.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplagbkzm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gtyqmfsdlv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtoecaopci.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtbruslxlc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlqpcpqw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehooxisg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtfopijbsg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtsaaymisr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtexjpolyn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtkyvvrlgu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtrudzzkhs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtimgegyeh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtnjpaxzox.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtvldfqhll.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtuuhlxojn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtswfyshru.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsprsfsfh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgqbrqvc.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtahqleofi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gthbwlqovo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtrrhqvlil.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gteausospg.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtuzmzdvmv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtvxrdnozg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtlbekctdn.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtahbfkrtr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gteqigayxl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtxfkhdsit.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtxpqftnwd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtdsgyhebf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtfgrnmjiv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwibrccx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtawyfebqx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtkuarekgh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtopskvdvg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtjwgteetn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnzyjsicl.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtgbhqtuem.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtptqvjajg.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtjufmnbad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtlpzdaott.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtsrlhjuzj.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtvninrriu.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtcyeudnih.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtddifqvei.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtyyiyfaxm.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtlxatclic.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtjoeikepz.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtysjhshew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtzlqpggpv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtjdabkbaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtrgjsnyqw.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtfgvfbrjs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtztwexwyo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtvnmelybd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtngprrtrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtlfknopzd.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtbwuicdpd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gtplxdkhuw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtjckpogrs.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtycclwmsl.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtigxalweb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyndumky.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtoongorti.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtqpqxzrgo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcwpvrdr.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtngkbkwyb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtgyajmbtz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtlbdvfqwh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtftepcagf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtivuxfaaf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtgqrbnqox.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtnrwgiqad.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtoafbidqk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtabcsavga.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtqcejjoaj.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtydjayrrt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gtvqsinnos.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtroexykve.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncgwykck.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gteifjuyfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtsawbdons.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gttipeemam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtjgalfpsy.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtqfxmhbyu.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtustvdwkx.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtuaiqycvu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtyqrggrpu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtzpoaflac.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtgirakiwl.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtulgyjqro.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpmrsyrj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdyxpsmq.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtymlaeqze.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gthmmfnqer.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtmwgxwefz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gttnebnyga.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtzhrtrila.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtxmipqdjl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtdvrjahtf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtwrfawsjs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtbmrfswrq.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtcbejjsad.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtwdoxuqml.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtxghmtbxx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtecuigbmk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtjpgjdvdg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtlvnitbhk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtmykirhbj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtcnygnmdi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtrsdktqje.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtgddrlukn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtpkfongls.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtejejzwcl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtwubtsbxb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtpjwnkvgx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtiipdmztk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtsbixvoqy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtocysxhcr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtwsjeirdw.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtmemasvum.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtsxdyklca.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtboxfaazh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtrkmgjity.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtkrxbziay.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtjgkgzxur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtftnurxws.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtdqqhjkfi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtskhzggry.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyyifplmx.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtavwqhsok.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjpjusecf.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtvozxxwar.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtyzasakya.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtviqzarha.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqiohepx.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzbyhuesf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtwkhkdzrv.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtewgiqysp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gteqyeiwyw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtbzkhsznq.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtwtyieyrh.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtzjtgwerm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkozrxep.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkratctzf.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtpiclycaa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteviroawn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtecaxjxlj.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtcxhjlmas.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtbhwqtxon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtccfrcdja.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtxdtpakqb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtwjbgqjyn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtbgshktso.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gttnhhwbxs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtfzcisioy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtijuamhzi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtlwhzdikm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtvglhyscs.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtbtjypvva.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtugrqnbua.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtmwkcqgam.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtxlvuflqa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtrzhrlpgi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtnooluiwm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtwscpxxfc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtuecoagym.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtqjqallrv.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtbhptlbmw.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjsaeuufn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtdqwtifah.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtquzguowg.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtwveqmeem.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtkurjyyig.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gtfhmipdcf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtqcbyxmpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtasliskkn.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gthyxvcwka.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtvlecjjfb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtjjbzradf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtblmvbuwe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtdzxhhxdj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtcxxjtlvz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtsmzugndw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gteinddwqv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtqmzzjdxh.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtlloxfgqq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtttdzvdbu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtggpihdky.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtjcqgasse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtkghwkwra.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtuvemmwnq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtivhlbbhi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtcbsbgdof.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtkzwhnyoq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtevjjxurm.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtanjvooxd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtwfrajlbz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtvvhzzfke.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtwilvthfa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtxrcsmuux.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtcniuefgw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpgnscwcj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtxiwnjgnk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtloowmsrg.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtnrmghchp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzpxzyqsl.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtssbwfxtx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtguytdvxj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtcyzsbdug.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtgxbekxew.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxawzvosa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtouldjosx.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtoviuxjiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtfjoaffmz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtaomnqzbe.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtjquulfjy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gttlxqlkxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtderpsiru.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtwyuvukdi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtjhgrjtit.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtxcxkrnij.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtnczotrvi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtxvbbvotu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtnahvxxde.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtfwetufhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtzxrnzovy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gttlbmtskk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbilsnsp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtdtblwmik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtvvknqxok.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtvmzasqhz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtyycrocbm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtpqxxvkvk.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbqvjoaq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtmlyfszaj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtmmjpahdw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtutonqqnt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtzfvagsws.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtoeknshki.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtdwhemznw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtztuprnds.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gthheezyee.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtaubuzlar.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtozprmpct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtepiivfhu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtogpjksct.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtfjylqsuy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtdsarwtjf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtfliojujh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtnmbnjjan.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gthjcrgtzq.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtavwwmbce.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtcohzfzpj.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtdfwahsdd.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtaswzgpqj.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gttogkudya.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtnagquakd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtsqcrffvs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtrwvvvwcy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gterioaasy.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtppkovrxh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gthervgmhc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtgrkevjwm.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtxpceakrs.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtmpkoclib.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtyakjrswv.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtbsxqwapc.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtxgvygwmu.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtivwcgkas.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtsysykvul.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtnuggboiz.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtbbkzcwtk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtikebmggj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtarsepgte.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtzljhvgwa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtctndbrga.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtgxluvbjc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtsemjcvij.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtubsuffpy.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtzakkmxxe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmzpycckx.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtmywhozop.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtqduxbndr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtwypvqvdb.html


<!-- 参考信息 -->