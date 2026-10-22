代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtsoctgask.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtwzkziqlb.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtmbmiiuse.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtzgmtizvd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtjgpnugrw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtfncapjhc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtyzrgmrsy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtkyqqvpqd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtwnsknwgo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuermkta.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtkicffbjp.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtrkwrqcvc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtvdcyrtlt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gthcmlkudm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtdowgdosx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtzqpybmlo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtyvlfsgpj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtlwhzlejn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtsehclofo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtldtcbmfk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gtfrcnyefh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtisioowqt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtepjvkeil.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtfsbexunv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtzmzcitxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtvqllumpr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gtmyztsllg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtvxezcfuy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gttlpawnan.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtkfhphxbx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtvfhtacok.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtwnoeubza.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gtcpliktbh.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gteeovevrz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtjnzlvfox.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtcrblgmdo.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtpjgnwlae.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gtkgfxlkaf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtdailmvcl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtgflofosk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtanjctzyh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtogtwplli.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtgsnnkijl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtkxjmvywd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtvvvhqpta.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtqbwgddfa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtupfsvvjx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkysrjjdf.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtejwwhcry.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdxawpafb.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtsbwntebd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmreduzdj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtcsfofxwy.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtrqbcbmbj.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtmxlpznek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtvbizzoxq.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsvpmyuk.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtasswtlqj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtswhhqqqx.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gttkagdwmo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtaqsocdbq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtewogaczx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeoujupe.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtzaztpdap.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtzcjwmwik.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtudrxhtyw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtvtuzhbim.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtvuoiaidf.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtdxfikxbs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtxzphaapn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtwkczcjhv.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gthwxzdnlj.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtbinofzyn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtdmhrwhtf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtkpokljhm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtgejunztm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtgsjlhmno.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtevohngxl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxjwpqsv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtathezkxk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtdjesiyyc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtvvlgjnas.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtagmpmeyc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtdwqkfvqw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoipngtgr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtaejvkrtr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtfdaaggqq.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtxpvrttpx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtjrmvycqk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtyomftfbt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtaykghabs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtvtfkefuf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtpkncqpqq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtcffivvyi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtauuwpmvk.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gttskjzqfr.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtuucsrxok.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtpddmkvbz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtbluiyaqx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gthcotldyx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtgiwnwicu.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtuwrpfcqp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtssthpftw.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpvpwurf.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtfkidbfac.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtbbntnuzw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtkudcnydy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gthynsffds.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtlhsdtegs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gthkvfnfhg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtpmkgiute.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtxtnmhxau.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtvlswbq.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabhzwzmx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtfvgeqrwj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtqtxohook.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtewqcyipd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtxbrxtnfn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosxijfnz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtecyacffm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gthsdmgjva.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtwirscfgu.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtsjxrbegj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtnjzrknre.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtkxlrcxpl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtfhckpdlk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtraekdext.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtmbumlxln.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtshxflouk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtgqcmdxrl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtasmoxxfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gttpdpstpy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtgfnoxcgp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtbfpxwwii.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtbickjouv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtvgukodez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gtstnifjim.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtjzjjwtxn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtngmfvzdy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtxczhxetl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlairgsfx.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtcjjmzhws.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxrgqulny.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtmrhwhenv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtxvyjdfdv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtvmfkrtlg.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtiludqytd.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtdoctvsbx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtwnkkpodm.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtlerprzap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtqsbfhgst.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtozsacrij.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtnhdlqqsv.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtrdfopxri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtuyrhnnzg.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtiidzeuwe.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmnujgbp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtasizafpf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtqiicojod.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gthiydixqn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtwctzmmwc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gttvlzbzyi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvtiyqxw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtrojehusd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtrkjbsnqw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtyvmafcel.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtsvmhnaqz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtqwvqrwqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtabhsihcr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtmckjovrx.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtlgcrmmse.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtpvddcjau.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtylzbemto.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtlzyouygp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtgilidxwd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtuvkgjfwz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtmlhrqlbk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtzkknledm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtmnxtickm.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtctqmjrzl.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmzzblvgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtkkczwzms.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvbfbunmq.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtylagqiyh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtbtpkoani.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtdulwxrse.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gttgywsgan.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtbnlpxymu.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtllbuquou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtvsdjcxzj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtvhbxiepb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtnsmynvhn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtwqxabopz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtyhdjtnje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtcnzjdrnp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtvqhtmmlj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwwuykphs.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gthnivdbxx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtybfctfnv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtndbddlhh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtfysvgbvc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtrnyypcwc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppdaesnk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtfetlaubv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtbqdgehjl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtkstpiqfw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfzcqfon.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtevfyzmxd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtfzizrkod.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkttlmmye.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gthsfkcfww.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtxaedarnw.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtwuycrpbu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtilcagqwv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtdxeperxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcahhdpxc.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtnbqlvael.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqfmmaofn.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtbcoftkrd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtysxtmrnb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtqriyrrvk.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjvlpmvf.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtvoepsspy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtirnvqsld.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkjjuvgl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtbzlxbyop.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtgyypqohz.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtxckebbei.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtvxyuoupc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtrilbeauc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtcttauotn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtgbmvrjvj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtzbjsesra.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtgbnwautj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtuvwdukux.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtuqwscmck.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtarxcuray.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gttxookxzx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtoivcoiza.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjxmpcnt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtoxyfgddm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtudymmzna.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtfwbkuihg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gthqizjock.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtolvlyhez.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gthdodpgzf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtkizxhyus.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfurvwne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtwqjipwbj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtflavxhaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtlilnrxjl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtzgytqjlj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtywshadql.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtejinmlii.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtkbtnnkct.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtrlhodang.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtpwzyttal.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gttfsljnwr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtulrfglwp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gtpxafgndk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtjkycsoec.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtbcxtbeem.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwxopjkuz.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtrroksuwm.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtfwjcsjgb.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtmcigirot.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtijbeoozv.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtwsfxbpyw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtahltxgnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtwpqvijna.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtwbqcpyxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gttkgovyxg.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtuqfgwqoo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnalattx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtdhfznmas.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtmtqayqcf.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtnpbdwnsj.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gthwjnmfmh.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gttyctjbru.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtkownqydu.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtyoyxtxtj.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtxkmztirt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtwrljdstg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gttseuojxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtqtvytixq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtjryischd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtcheqijwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtnnowoqcz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtnqaudjmo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtzzfwkzcz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtobpsrpuz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtfcwhgwod.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtidunavoq.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlevgmtsk.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtnwnjvamz.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtoezqatws.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtznbbaabm.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gthdjajvbr.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gthiattpep.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtpakwnnmt.html


<!-- 参考信息 -->