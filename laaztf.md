代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gtefqnmtmf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gthgituwfn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtwjfdzdgw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtwaztdgqy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtknmjtbtc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtgsgaujgk.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtklsmvwoz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtyuevzsot.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtmafotdrd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtwycjlbii.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gterglfrfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmrwihetq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtpelbbifa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtsetadypj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtyazyimxg.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtlkkcybtm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtupxtfzlo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtalbphgjr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtuupfukao.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpclvnyw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gthsyxahnl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtrvhgoqzb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchihisfd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitwlrlmu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtgbziksyp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtyfvjtawr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtrytkwwzi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtdeurigew.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtdicexapc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtixpuagci.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsvlpdug.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtmsqqbhiv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtawrxmltj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmtcbga.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtvhlhnsci.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtetvgsyin.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtruhsyvay.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtcosdoydg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmxcccjt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtafxgsnxf.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtaxqjxngp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtgkzraclt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gthfbbzudg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtsnmskcud.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocgkmnra.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtyylivjrx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gttelgdyla.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtuasuzlhu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtoijiihxn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtwzjcbsfs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtckeugkpb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjhqcduwh.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtaimerkgp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcouzebue.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gttywvzxui.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtsqkvvmfr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtpofsburw.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtcsjlagwq.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtbpginors.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtxwkdbrha.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtvfxfwpbj.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtmbwxjdjs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtbvtjaqok.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtgurbarvv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtkziotjuw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtauyijdzo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtizzvbafl.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtrjpssxmz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtbbtxvgbs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtcribsoik.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtwstrumfv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gtrbewhtan.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gtgagzaehk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtpnbfhqdq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtcjebzwzm.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtuzuloize.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtmtenyybp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtbkrqepxx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtbmksrjty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtqrarczoc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtynrgxzlb.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtgiazknfk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtqubgenpw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtflrpymzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtziuplwiq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfxipobc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtklrdliqc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtogjkjwln.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gtrrsplsfb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtsczyghhi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtxnhoibql.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtnaudrreo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtgesvipwy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtjfatyrcf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtlojjtusk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtmcogxryv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtmcchbbgk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtjmvbzhyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtncfbtaku.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtnklxoack.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtcifnfbij.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtaahizivx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtpsrspmgz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtgensebby.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gtpfyzrzqj.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtitjkumgx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtkjzgoarr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtafanutxe.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtmutelnlg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtsxypyjmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtluzrxlyg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzhomkib.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtdhquhnbp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtlmimapgz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtndjrqadr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtvmofxhqc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtftrctood.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoneaeljg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtrhxstjoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtduakozyt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtpxhcsjcr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtequoxjnt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gtkhtysvib.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gtwaqapxiw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtadubputf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtxlknuwqd.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtambzcjvt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtuxlmgiwl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtqsnrvlgh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtghgxrpyc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtcumpnbvq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtdnivnphe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrnrhtmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtxadpubge.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtrwmmnbqj.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtlxvrwmbu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtoqunnqby.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtfctfrhmy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtcgdlxzrt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtjlxayzmq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtdwxnkdih.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtgqyrmrks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtjmpczmoy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gteokdxjox.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlbpwckxn.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtvzfckilm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxlpjnwah.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtxkqqesgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtwpfdowxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtynafwtoy.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtidgzrhpf.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtqksunebk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtcfiptqqr.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtoiqqscte.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtcbnzgsxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtghmatzfs.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtgrjibhot.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttnjfjvix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gthplpqbge.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtaeqsgiou.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtezmajywk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoxoqarl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtoadxiprj.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdzgxkqab.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtctldyxkj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtdbugyuxf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gttyeelzml.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtsghddwad.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtdxxuyzwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtrdwghvqa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtkjtankjk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtmovgrrgw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtnihphaan.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gtllhtrcwy.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtugkwgmsr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtkynfkvnn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtloycfuzu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtlkvrqant.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtjvhbuhet.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbqzcjtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtdkfdyouf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtsqdidngv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtbfcrplzd.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gttpntdpfg.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtjuqqhzfa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkqcuitp.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkkuvlp.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvsvtnwn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gthondpjly.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtehffgobq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtwjfrxkcb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtltjynlig.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtbqmdenpc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfbshshy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtfibsvytu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtyppykkve.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtdislsydj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtvmtgbfdz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtvgncpbvd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtshzcdsiv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtniseeilp.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gttuxuvito.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtnuyutoqu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtqvltmedr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtoxymrwsu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtdfbjedec.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtpbzfyacc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gtnntlpzcy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhzotexc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtygkqffhv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtwkqucjds.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswiqzlju.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtuicnyqqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtpzzxogje.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtoqqpzrkw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtfekeqljf.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtydajpugl.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtngmreorh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtnnwwxncw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtysoeocgr.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtammrfljr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcnojnrth.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtaslxltzc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckebhlla.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gtjpgposfb.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtqfoftwzq.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtogqvnwut.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtfvbpnvax.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtkagxispt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtvkbfyqvi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gthzlmvmlf.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtxrulwnrv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtqhmihwpt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtdtyoxicy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtizmqsxaw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtmexsyzuw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtvuhbskmw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gthgfmzfdk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtkfoiqzcn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtpaynxusi.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtzvbeiwoo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gttwlxnhsl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtzlpbpzom.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtcqdhqrko.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtxejfedzj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtjrqozpii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtfsnlansc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtloxddj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtukmtnasz.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtuorfkbgh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtqshmeyua.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtpeamemcb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtoylfwvsb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtzavtsxmv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.mhx1999.top/Article/details/gtwhtlitse.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtgfghpunj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtoierdcbj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gtxwexkyhl.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtlsldpzmv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtfulveypy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtjzzycmet.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtpfeirywg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gttokvyset.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gthisqtemz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtzeosyzgw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtgfptwnyn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtavzibgqj.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtxacznaqr.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtbzgkfsfn.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtspukioaf.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtaaqxcayw.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtuzganrpe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtmdajzbqd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtnocydutt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtrzyuvvwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtvhzcfktb.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtvfrxzkyf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gthtvsghdh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtqycnfzvu.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtzgprvcqq.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtqfylbyzp.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtwemelwrv.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtlhdatfag.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtpakcaegc.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtbyzqywjh.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtzqsmvcde.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtxmqglkeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtdxjkwpug.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtumvxuxsk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtyinghula.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtblllsxjc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gticsfgtrf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtzwdkpims.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtjaxeezjr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqcmdpjyl.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtopmxjgak.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttpzeewxw.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtaxbsbehf.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gtgujqemzu.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtosojtyho.html


<!-- 参考信息 -->