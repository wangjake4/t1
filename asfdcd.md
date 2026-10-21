代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gthwnopvvv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtoamaumkz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtcfoprukb.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtpmccgorn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtnvzwotex.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtzwtmuipj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtfkbqbros.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtixmjuxfj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtnqvjvebh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gthlsynjmx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtraoipkip.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtduaurkxx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtzzdninrv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtabzhdnug.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtdwjpsfqq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtxlcexusx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtjbchyphi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtxnpzwvrh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtwgqmhtbh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gthgdradhe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtpgolsdet.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtjpghlwse.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtybxartsr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gteqhzdscv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtoclnhlzu.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtvsxsbsap.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcmzvhhj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtqgurumdd.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxxsjtho.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtvnooinos.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtslnqlchq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtupebunzb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsxxztyp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtpvoqdfvh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtmxbwbcbo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtmrcrxlfi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtyvwpxhhy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtfymwkyxh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtqetsjjyp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwvjianrt.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtolweernt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpohduand.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtdvqccxem.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtfsbhhiji.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtjxfuvvdk.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtoyidfsrv.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtswrojnoe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtadhthjlg.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtjaaeaqeo.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwemlxou.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtoebdfhki.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtjpvdpubq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtsrjpihgj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtobiqfwan.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtwbtglgvg.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwlgkpup.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtdgpetdiz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtamwdueqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtwkfutbrv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtqjhhwiut.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtsyrfpqcn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gthyrnbrhx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtlaanocpa.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtvfqypdhq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtlhqebvls.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtkrwhftnw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtyzbtgvnq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtsnwthpss.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtiphmielo.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gttapitycm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtxfmbyfgw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtubwvfied.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtueiiamtx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtajkkbhga.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtozhynons.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtrnpxmkte.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtcdenwrax.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtxfaggags.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtwlcstrsk.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbwiyuun.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtmhxlnekz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtqsdsxbpx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtxjmplmaq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtdqiubzeq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtgkeeivev.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtnmjcsjgk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtgcsucezs.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtkyduztle.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtyhiclrdq.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtwuuqpbuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtlwjkjdbw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtkuzbtgmf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtzxliolbf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtxhcffgwv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gthdmrdfzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtqwmcxszm.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtxvgxolva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtozeqgblp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtfxqsnypv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiibrgwu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttenpfmxt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtjxgdpazd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtwgwzcosi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtjejsboae.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtpbndfske.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtnpnexiow.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtfarlahyf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtpcffchrp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtjroaowho.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtyrufdthn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtvsfdfvba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtjspvtpor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxtbeghw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtgxkalfcc.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdtjofcr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgpabisc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtjwgifniw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbrcygjj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtorppibqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtengfcneb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gttoucrayx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtkyicyngg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtpnuynwyq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gteyryusxv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtvbgvshkl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtarrdlrms.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gteykdzbsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtnkapchbl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtllxhpwod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtaqmpjbin.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtscbqmpmj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtipyqdtii.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkegffjwb.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtilcrjexp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtselcfdhm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtmmixhlvm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtxtnivtbr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtbszgjtum.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcvogejoa.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtsntlbuoy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtlicbxpxd.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtgrqoczsn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gthwxeemdg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtstzxmrrn.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gttyethjct.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtjzfxowfq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtzbcberxo.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtrfnoeyvx.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtqvasuuvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtqpgcepcs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtnrkbkici.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtfhgfoply.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtpllvhmaj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gtcputmadn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtkcksgwzi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gteyoteiey.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtcmkmpyry.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtchyrnani.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipvrlbqh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnvvsjdk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtybzyajhi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtmrbwpelf.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtllzlmsse.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtopprnrtu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtakkzsfpm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtybgphocy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtxubztlwl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtjwiwkmux.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtlyhffbxu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gthejduqmz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtnajvascs.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhezwfgh.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtgtppqhqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtolbxbxnw.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtcycsbqpl.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtciguqywp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtkufgcjnh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtmbaecist.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtrsapuykn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtgjhqoeag.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtccuatuwm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtkscoekuf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtszjrbzrq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtyercrmjo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwfmxtrwo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtxmqvtoax.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtptrwjkxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtqhqrhfwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtqegqjxxw.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtjsbykrxt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtdjzwlssy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtlinvxgzk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtbwlivnxg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gteknigzka.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqklswisw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtgntkajli.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtcwdxprpn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtkjfwplgu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtggxdrgck.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtuiyvjaxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtksgxvqtz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gttomuditf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtqrsunwsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gthmwmvbqr.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtfsezfhly.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtxycdoftn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtggsfrjvz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbbmufhyt.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtgtqmgmkt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthkwwserx.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtduoraxwj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtwquvwwdd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtnxrnohvu.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtpdqkwbgh.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtiolifyrd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtifsipfmh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtymcliuzv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtzxdlucub.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtnuurnmwj.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtdkvnbnwc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gttvvgqlvi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtakbzjuqw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtssivoena.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtzonaqfzq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtllvsgitj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtdymvpqsn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkzjnbnu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtwimmgygl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gthtzhxfxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtunjmergu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gtpdlhbxxw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtjtofhvhf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtgefevffq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtijwsgsrc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gteagmwhzz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtjsmrjfys.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtiahjrjtg.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtnwmziezf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtdqrnfzkr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtmxrwzybl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtbodsfxne.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtnftcxpys.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtytchurvb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtjooradoe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtxxpusfat.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtmseiziqq.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtfsrpulii.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtbljihqau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gthhlyajtb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtooladtxk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtxjrizmqc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtariitjwo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gttcsfzylr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtqclfaayp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtcsueqkva.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtluipwbdd.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtfjkmqklu.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtkbzaqrqp.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtsnhpzebz.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtfnfuiwqx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtscdbqnmg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtahwdpufs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtvuqxcmzi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtcgzhjjrh.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipqbqqqj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtvvjcftqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtvpskgefm.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtqadzncrq.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtgtubhxbd.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtkmjyyhrk.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtuzkskvzp.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtcfdfhpia.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtjnwnwtxf.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtjywojyib.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtjldlbmqq.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtqeixnlkg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtwneesfqb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gttaphovlo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtwzyluids.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtjbeocnpk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtbndzlyjo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgnyzwwm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaclieuts.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtyxzeeqel.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgamjmqjg.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtzekipopl.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtpdonxkyf.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtsdtjupzy.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtkfajxzov.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtzzarfvwt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtwbfpwcyh.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gttynsaagk.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtakdvvixk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gthmirsykf.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddmrzwjz.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtxyjbolor.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gttcbyhexf.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtbojiumyo.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtaiqbtznl.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtqchlvfto.html


<!-- 参考信息 -->