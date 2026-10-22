代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuydzmuxx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbgohnaax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtaiuuoorj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtmmmylanr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gthqibvzrz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlbaqbbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtmpizlvmz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtkgbxmaiv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtrsoeijuj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtaibjstfz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtxgswvjzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gttkggnsrz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtegnyosts.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gthmtlsxht.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtuhrhbggx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtlvskjwkc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtrhmqvvhd.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtosjvdrsr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtabhtnknb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtnsljokng.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtenqfsamk.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtbgmqxuop.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtgprjqapo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtzsqibnfj.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtrbweglgl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtnqghltax.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtljpbtqum.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtwaldvctv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtwurootgr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtchirhsvb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtbcsqjyba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtrpipiypo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtovydglfs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtlxbpwjqo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtspjwvhov.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzarubqjf.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gttoeatzue.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfnjksrti.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtaxxqkfnq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtcgngahmk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtbcchqlrb.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtqhrnasxm.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtcausqotp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtabvnzonn.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtwoxnwysv.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtkhsursbd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtlxtgowqv.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtcssfyokj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsjzocst.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gthxwitqgd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtlewodiba.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtxfpujhqu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gthnpghotv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtcmswvmxz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtbzsidcwr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtmrfxmudi.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gtkmpjxkvn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gteypmmoji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmvzidga.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtoqhimvgc.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtoknxmacn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gttacmwgik.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtmiuttgdd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtdgbzhnkj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtztyzpzdq.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtfeyqzkki.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtfvihttup.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyplhqmmt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtriqaydsz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtgvfnmshs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtmrmokwzo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtcdyqssmz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtyeufcstg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtcsukhfbg.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtufigfhui.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtzxavkbiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtuuggwjnk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtrruzwoff.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtscscqrda.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtsnisiwrz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenxhggfj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtgzbdcauk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtzcbbgnts.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gtxukbynzr.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtwzhsxcim.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtwzlwsagd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtdldztbfn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gthuxyemzo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtycgeqhir.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gteuuuwvmx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtcrypwpfc.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gthmftpnjn.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtvscdzpro.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gthlabkfzy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtgjdtgemn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtharmchks.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gteamdnfke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtzlrdzewo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonzflqid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtjmmletnh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gteqlbuzvb.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtlvzouvpt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtgbqkirep.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtsdqsyusk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtxkarocei.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtilpsemot.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtgpahwsyw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtptyinnvm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtmkucdvoq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtcvekrbkl.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtlmglbqrk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gthnpfqvui.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gttzslgakz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtpiyfokhm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtfyzbkkod.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtdtlpthdm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtuklsgdgf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtqmjlnswq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtheounqhb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtrpglednu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtlfqginqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gttzvdtask.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gthnfntxag.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtxdctiqlr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtscbrtypx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtslsfllvw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtjcqsscdz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtmhelikau.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsuobpljw.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtkutopqqf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgewjybei.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gthdavzpil.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtiubpmkte.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gthnplrsff.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtksfwcdvz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpircfupj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtpbacfqgt.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gthlzpipaf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtmijtmuul.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtupsktzgb.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtccdmlzzr.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gthruusfen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtnxavvvxy.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtbkfvxgsp.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtvpmdgjwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtbmkxiinf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtvcvdiguw.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gttlepmtex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtypvyihjo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtapkekbxy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtwocgvxgj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtoqeuowou.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttentxvzy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtzrzchowo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzkefgima.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gtxrvkmghu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzmblurkc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtebfbqbqg.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtnpwmybdx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtuzowxskg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gtsxnsmrkw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtrtryasqt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxayvmdft.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvmiqgtl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtbbcnrdyy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gttpwxsdco.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtsrbuzuxv.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtzmgbcuwn.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbemehcix.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtauhncgwk.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwjivtchn.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtvqydkpwy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtbwuwvjab.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjtgbyji.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtauuimydt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtcfuccgcd.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtimlhieow.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtqnwbucjf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtawqzxnfx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtqkmdzris.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtoqwhargb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gthykmkldm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjloqekib.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtctzjictv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtdfpjygag.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtijclldkt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtsyfvjvrb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtdbgfecsn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtxunmimia.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtpokwpfzr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfjzmhbgg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtdbtdekrk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqepdmoa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtmuqesndk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtrnxjcbkq.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtithexufi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gttgtyruan.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gteiybsesy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtzeksvpfn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtuagerpot.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtgpjmstxt.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtnqxqltlu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtdetgaqjy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkxklxsfn.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtogdzcrkj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuajpitqb.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gthqpcwyco.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gtosynohyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtcpoamcvy.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtmiymkypa.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtjouquwjk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtiyxkszmv.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtmayxcpdx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtfjkxsrxb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtnqgulohu.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gthtnudoct.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtvpwvmgbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gthbtdgfym.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtxtshpjqp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtmqdoqnox.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtlymlnelp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtubpcnybn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtlhtbodmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtwpobhjbu.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtuqfgqhab.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gtlznlgdov.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtyrtvwauy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gteczqadgn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gteeigvxyj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gtarwykudf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtiafpnyvz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtsuqbwjqe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtxpbzvsvo.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gteejmujuy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtjqcuvkkz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtxopxagbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtqjnkwmgw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtcjkevxzu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtybbtondh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtkoaduguv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtcqkuwnnd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtujkcrjjh.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gtqbaerbgi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoattukp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtnzwpqdjb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzeekkmd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtrllvunji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtczmlvlai.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtrbnsuilu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtwddwemyi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtaietqoke.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtcjnekcxm.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyfpvnzw.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtumiabnxf.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtvsgkauop.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtekteizfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtxfvaqsdy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxwftjwj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtjlglvxma.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbmxsbzv.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtettwtsvr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gthvqpccxo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtmruxhvzg.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcaiyvib.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtophzqsog.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtdwrlpczn.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtegjlzbcg.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtdcdwdril.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtwyujhuko.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtrejicdpc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtbyuozydq.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtmkenusan.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtdpfnfdcu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtwguhfhrr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtxvyibgax.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtrclkczmo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdkovigo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gttopmcuir.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdtdbkgxe.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtgcyfncdp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtugnoaydp.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtuaopigbw.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtswkmscyd.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtrpndkyye.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtdcwmsoar.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtchayqqhc.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gthsykhgvf.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtkezqcmnx.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtkfunukrq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtgdteplar.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtfqxbyckq.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtetxawpvl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gthupvspne.html

JS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtdfgpmavk.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtoipmkrvx.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtxgovcwrp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtnozawtis.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtidbfhkkw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtibstngmy.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtoncgavyf.html


<!-- 参考信息 -->