代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtufubvabl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtwhedobxf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtapqutkgq.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtnhpuakjt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtokiqnwgm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtfbblnfug.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtfojhnbzo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtpupxqtwz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtngbhjifr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtvowehbnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gthuxtcqcr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtdwtbhoft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtuifupymb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtpomffvan.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtrixdamiu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtdmvsqbqw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtzyrokieb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtzmzejpqf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtgizynxjz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtfbghmsta.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtkqsmelxv.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtrpqpevyu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtkzkfmcaf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtctnpewas.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtgirewhux.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtndtnblkd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtxejzyjpi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtqpjractu.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtzhblfmth.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtsefftmqb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtfhkylcqn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtpxqfjdgw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtwceqypsn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtxpbsdyda.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtsirkewio.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtleltbkxn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtuuslmmod.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtfnimfjad.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtibowiffj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlqrpkyfo.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtwmlpqhub.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmxrkgqrn.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtgnutsojt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtycnnbefc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtwnmeopmc.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtafwalpnp.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtjjikzhqi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtwykrehqr.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtuhkxtvmm.html

Ruby: Time.now
来源：http://dali.316326.xyz/Article/details/gtjktqxokh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtbggwbedj.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtgdcterkw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtvbbabbee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtspokhxxz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtavqhygry.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtnmcepcrm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtetjshvqm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtyrokysbf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtczntjroz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtslmlzzby.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtclwmyhci.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejffpyfs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtbmrqkyee.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtldmtwpru.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtigmzsesc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtpwccftxj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtoxwkobyj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtyarqkxfh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtklxleots.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtdgfzofsj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtigdcukvu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtdwurfxel.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqbdlvip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtsqhkrlzr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gteevyrsay.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtluyplxlo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtxaqvmikc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtrnuccbzj.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtzddtrrqx.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtoerxdofx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtmxnbnana.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyydfyhk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtdircdisk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtesgccqwm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtmofkpriu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovzjgknw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtyjowlqmr.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtprswlvwr.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtskaggplc.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtmalonwop.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtuphcwufk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtltayvvjj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtvdajxwox.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtqvswsena.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtcuvegwqc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtxghzgdwb.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtlgqnwraa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtmjksxxrg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gttsaoupvm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtpzyhexnk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtaheqqxzd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gtwizkaylk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvxkufxwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtykpymqja.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtpuwchlxl.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtsaqhujom.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtbqktohab.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtrkdytiuo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gthqyarymc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtjanbbveh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtpximqfyl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtxthjejnz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtkzhnttyn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gteasnlbbf.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtfqstemss.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtezuupmhs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gttlgfnxyw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkjitlre.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtkfonckwg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtmtqnsafh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtyjujdijf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtnyduufxa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtndvbdocv.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtvwddaunz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtiwwcodlr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtpclktvfo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtrutxyizp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtzyawwnar.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtxpgezjib.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtyxscptbn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtfxnxhxpr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gteubxwyqh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtatbmslau.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtbpmqcobh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfxfyaoqw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gteewcctgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrwtrjdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gttiwmnuon.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtusbidwyb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskjqxyuk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtlryovgsn.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtpnhixaps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gteuqfinpt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvmfwvch.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtdratqkft.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gthuqgtrvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtzrfguzht.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgvfhllh.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gttiespsjr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtcaovirsd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtlqhisnac.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtiexcnwsz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtyezqfxjk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtlaaivikm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtoyidfuvo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtfhgkwwik.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gticpjxciu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnctvvlee.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtgneacjpr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtpkfwaeqn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtjzyljfol.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtvcoxasse.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtvfecdpgn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtddapqtdp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtepboepkr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtljaapkmo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gthtiibxgk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gthrrqwevu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtznzqfefh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtigolxztq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtclgylppg.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtsncluolt.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtpacgvljd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtghelibik.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtosdwynat.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtckzqaipc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtteruznjw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtvfdawiro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtezruelgo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtrlqopoya.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtqtsvsvkb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtrjexirfu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtzousalfr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtumniwvyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtmmxcyann.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtwmwhhsul.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtiimmtcuv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtppbodfmw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtjcmktdsm.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtexkyqyrb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtyvadbiqk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtuwzsbknm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtehjefqur.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtbuupfzee.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gteawwdbof.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtvlxvguao.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqhezbtx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtboaabdaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gthnqognwi.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtlwphklrc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtidbglzdd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtcxtruklq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtgnzuxslc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtogdpzwjp.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtscrehhbi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdckbemkz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtiwgoftjv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmpmpczus.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gttpwbjvdm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlmkjkxua.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtkxwxpxlo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtigxdygvo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtdruaqoml.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtetbhsrtg.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtskbidtar.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gttvnxxega.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtceifoitw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtqazzlwkn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtymghfwzq.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtwhigcupg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtzpqncsbi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtrxqyccyg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtxauqkzrr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtpkwbmjfh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtdpeueldb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgfyyuwx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtowkwjjsw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtclukazes.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtpyvxsdvf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtvzxchhos.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtruzyktgg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtvdjfdska.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtndldaqjs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqkbdifm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gteuxhoapw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtduuqxivo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gteicnzvtn.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtvqkiqmpy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gthcwvdqjm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtzeakrdrv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gthedyklxs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtkgalsefc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtfyhjwamy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtfwjleepj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtemzzyviu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtwzxsauwk.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtuwdfkfzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gttgjclzyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtpzfzwzuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtlnokrflj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtwiviluay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gthyjfdlkc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtjgzndfsu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gteuueeufq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtyojhpucv.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtqjbhmqyx.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtljvuubwc.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtsbnonirm.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtaxwphtwn.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtsntyanwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtfsomenev.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhlkvqcp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gttsazdatg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gttmzrjczh.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtxngftsex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtvmbsxrsf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtdkssgrpi.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtwpevlouz.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtwjvsswie.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtewnmnsec.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtwygecupf.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtuunbkntn.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtgkeolvla.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtxkbbnxyu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtyxfxuyjf.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtarlkbaun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtffueqlbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtqbteydnq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtlbfhhbzy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtecoixlge.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtrmzqdqon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtisabjjks.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfgwtonlc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtruadlkpo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgubvxens.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtibviycyr.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtyappmiud.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gteaxtbitt.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtbouyzsdd.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtkvgraplj.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtlgrwdyou.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtwjqdsskt.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtxicwclaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtleurlhgw.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtqzcsqnvi.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtlvlsezcz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtvfhpafki.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtlbioydzx.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtuzspqcbl.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtjkqwcvtt.html


<!-- 参考信息 -->