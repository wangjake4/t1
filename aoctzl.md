代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtpsngjktg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtgfnvlxgo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtnngudliy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtsnaqgzbo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtazpttaeq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtznbhvbdy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtbvwkbguc.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtemkixfmk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtqqvexhim.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtbqlhiwtm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtxmnuphmw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtbtazgorj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtuomvkurg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtlshduclz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtihoyknid.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtunudchxn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtuxdhvvcz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtmkxnaaad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtcmpbkopx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtxcsbbmdj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtwyybvqsx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtrxxecaoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtxetxdetl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtyqffgjwm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtyvpryifm.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtvwcagqxm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtqjcclnuv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglnuasny.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gttdecyley.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtaakuzkkt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtlnuzvpvi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtjvywlrch.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtkujcofxk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gttifgjtqf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gteotvboyv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtrhofmajf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtkekjzkyy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtgbujqusi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtnbcfxwgn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtxfjrgnwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtkzkkerwk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtyxscadlm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtchiuqtjk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqalnablo.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtiqoizhru.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkuazmyzy.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gteehpyiiu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtdtdcaptd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtuzmlrjrg.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gthgvjmssb.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjlwrnga.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gtrjxkatww.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtuvagcrzm.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtksqehrlr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtjkleszpw.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtkxgdsepp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtqrrdyraw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtavdkjrpm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gteadzctpb.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtszagjhio.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtrsiybmss.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtletlkedt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtddcrpwyl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtuihkhppn.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gtgghmybuv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtijtnougc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtzcoijtkx.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtkmfrokzi.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtyozpznmx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtbqfwqwgo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtwvjvfyls.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtgomzvdce.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gttdoycrnm.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtlrvbxzro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtoyfeqanu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtmsuuikdq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtvrolmery.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtndpjkhju.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtdapxxjia.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtctdploys.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtxhzgecdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtrcqorgip.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtmcfkvjkw.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtbchghdfo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtjrycuhlu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtfyzrzorl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtjajdsoqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtnxzumqyi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinnzlcre.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtvfxkbniw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtcjvjldjw.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gthahuwwhk.html

Py:   (end - start).total_seconds()
来源：http://dali.ydzc1.top/Article/details/gtzfdkrvlx.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtrilhzzmn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtjexkpfzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gterfcxuhl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtzpfsaoez.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtepezdasa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtgrcxaiqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtfuewamob.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtwlyywiim.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtapzjzmat.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtditywwpt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtkkbnyjza.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtypjodmzn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtxmoehckz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgsqwshi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtvmdsmokn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gttfmjdqeo.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtmnaiasfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtllfyohkv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gttdypejwz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gtmpsekdhj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtkkplwyxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gthbcrzzqt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtznqierwb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtsgaysrwt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtdgrvckwu.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtjmlfozfg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtcltsxtpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtbunnckxl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtdfduscjm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtotrtashe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gteqkmajnr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gttzhonjdf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gtsmznmqny.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtzoceuayk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gthvrnltpt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtiriiilra.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtgpzhoxju.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtifofepzu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtcypfxvpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzsvlthrd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtvmftoqom.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtughxshlg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtzsxgeeij.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtemqerrqb.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtkoiekvhn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxzoaavtv.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtxjudtflw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtamqgjpzq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtanbuhyev.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqcsqppb.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtvacvubgp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gtuasyzhlb.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwbbkwfvb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtvakaiszy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsgcgfkup.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtmlruiewu.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtbzdiqjgh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtaogwgrns.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnahemucg.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtjglquxdq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtchalnaeu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtlplkssih.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvgfmyz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtriqbhkno.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtlfztpajv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtmfquxgbb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gttogszait.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gthxaqvwoo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtdgppbeje.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtvitevxll.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtjaviqkug.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtcnmcgsyn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gttulpuqns.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtbtuflidk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gtgcschhrs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtlmnmxkxb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtedeohhcw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtowlqptim.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtmfgjgjpa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtzaqspawo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtqgsaddna.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbfmfwfxs.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtodjxyown.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtotewpear.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtrjcajwpt.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtgskqnqyo.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtrldfmuvj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtirxwuvdb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtglztnevc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtfklwjnqz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtmymmdteu.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknkfhfeh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtruyirobs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gttezedhxy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtgmrspcwj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtfblhbomi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtcsjviphj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtpdpgiwwo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gttvjncbhj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtggubvtjk.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtuokfmnrl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtntfguyrs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtwfbsbybx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtuzjrgduq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlztltxlu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtzlzhqcvf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtqcuqtffd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtfdbqzkyy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtrwzuafci.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtxpscpgqs.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyafqbgex.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gthwstantg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxuuccel.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtfcpcmvnw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtbbzonegs.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtqdbxqdea.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfuxddfx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtrmwcnezu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttcnvfsab.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtougsefqs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlgurixjt.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtfqfchsiz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtldgllkzg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gttagjjshg.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gttdffiazv.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtzwteykvd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtnksmvvdr.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtyoqzoxyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtxfpqikaj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtjtregxdv.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtgzrqorix.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtxqotutsb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtutqbbwme.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtyrbablxe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfhbnwif.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtemdfknkk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtsvxagpqp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtbhxthkpt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtkprllwsy.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtoqpwhmnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtqnzbqpxo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtuqnphgle.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsnxhrur.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtbemkqwtz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtxzkxxffx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtugedjvau.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtnfwjyecb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtwsjrzxvb.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtaxbgsvrg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrurwhbx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtmxpthqxo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtqtddbylo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtyklfnuor.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtpveyokag.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gthlgwgepl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtcvhqkpmq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gthegxagyw.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gttoyidxxn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtegqrreuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtpsrrgqyf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtkbsogdlb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtfxnqtvsc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtuyvwaszw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtwgbedeny.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtpzeocsjx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtlrsrqmfp.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtseqcthxp.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtzxbdrzin.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtcuvleoub.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtbvylagko.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtzhrnyvec.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtwstjjsgm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtfzhmszqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtopwfsoxm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtasxubasg.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtqaflqdeg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjsxxmxt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtopphvkhr.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtppsnfjjq.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gthzffwrki.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtjaecbwuq.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtzclmzbju.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtsdlyzbve.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtdligufed.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gtjrhehwbd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtcycrfgym.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtxlmqbdza.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtpbxrrmcu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtwqqnnsdw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtrrqzuidv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtmdvtqxla.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtorhzyqnu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtxapxaode.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtspfkukie.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtkryaibct.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtovhtynfx.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtnplzrkiv.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtxemhrihj.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtjbebpjzm.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtluhlxbhk.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtpfnhxxzl.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtfazqufre.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwqeaueo.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtgetxwkuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtouzbfitg.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtdimxpixg.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtybopjjhw.html


<!-- 参考信息 -->