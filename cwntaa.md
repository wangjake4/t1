代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtyzuddmvm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtupxgfazp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtclibirvm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtvkzayrzg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gttyeuuuvn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtienjngam.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gttlpxcbgp.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtlqwfkfcn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdaymuec.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtwldgfqfd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtukybsizg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthozumsim.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtsniqzbyi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtujdzfbht.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnjohezts.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtrxoatyqx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtkhbdlule.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvgcjeww.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtixuefvdo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlycivif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtkuwmlveq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtsobanhfj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtocifezcz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtqvyijlqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtflsttfve.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtwvtrvlpy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtarzrvfol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkglxtrf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtotxeojmr.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtgzzrytsa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtrviualtz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtnoxoypzi.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gthvfpdlwk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtmswrxlqv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtunovvhug.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmukhhfjs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtyrcihwsg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtakjzfraz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtkiswkpie.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtuwantsdt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtbeumrsbb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtteyhmqev.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtgtarjseg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvmqwtkrq.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtwfszhcsh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqxqueqtf.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtdengfyeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtdjjefmcs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtxifxqzos.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtkvunetyt.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtotzdoadr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtftmsdyoj.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtaorkyrlb.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtkwhrmgfy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtaehxkuez.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtyoscjjfe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtqlhjacrl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gthxxvtzve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtuzxivzpr.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtjtqtqyil.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozazrblu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtssdjzfqz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtfoatcsuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtdxlzjlml.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtxfggewci.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtgepfmmop.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtfbvxeqlq.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyxczioj.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtxzbzfifp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtjoiyqmxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtcaxttjjh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtcxpqoppy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtshabzgbk.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtffcolcgu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtxzfmzajl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtoqpqehdd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtlfsihddq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtplmzedsv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtnmxickav.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtdpnrbbyq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtucleqweq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtjmyxajhg.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gteipvkquv.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtcyczicdj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gthmnrnoyh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtmxlbftup.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtobbywbti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtqrdasblk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtonmeaezc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtmzpnnjlf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtoakdpnot.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtjsykknko.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtmidkageo.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtghewnmht.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtzdjrapdp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtboqnndbx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtqvjmxcav.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtfxisypdq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtpdqzudyd.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtksjgiegw.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtgwobffym.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtjnpsgdou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtkfikcfms.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtejtnvenx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtholdtpiy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gtgvihejfu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtjcfofkgm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtnepslbhf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtrxumcuib.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtetzkdjbc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtnkzagfnq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtlpcucjdm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtcnoqllvt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtlxgkrckw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtqeitpuvd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtkndcfaur.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtgpgqmjlh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrmitggr.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtyssayzax.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtuiydseet.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gttnzpewbg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtrhrrbhdi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtlwhcrbhf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtlgypgtsx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtcaufgvll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtqlidhyag.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtvhzdlpis.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtglfxaqqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtfelbbkxs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtaoumsbyv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtrlyvhvso.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtemvtknaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gttsnrzvcy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtflloqrui.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gttjeevdgx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gttzexrrrz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtueyrhabr.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtuomwtzmj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttqktohhv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxmukfks.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtugnerfmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtzfpbfeye.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtydmscxnf.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtprlbpfsn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtfelnnhtq.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnrkxwkoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtqniwqarf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtlnqziuil.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtegmyvcak.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtdogtinhn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gttqzfbxrk.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnqdxevwg.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gthoyeqbru.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtwhrwedxb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtinzayzkx.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtqkueardo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnfvezolz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtbcvqwpnr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtbimzicuz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtigkxijrh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtgusykntr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtoxdlcfdv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtymffetao.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gthdokqdgx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtvtsopcjv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtxpcfqjrs.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtoewuvnzm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbnpqujky.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtkgtzpyhw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtlqqflipc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtpzajpyen.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtzccbhqgo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtlcgcmgoc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtpyoucged.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtwmarhuji.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtqvokcjmi.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjeaesfp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtyigqlsfj.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtflqfcqhs.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtvymysqqs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtxkjrqzpb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtprfengzm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gthugjylsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtovwgorrt.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtyhdsqywo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtdlyqmekh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtiadhgvub.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtberoqvsp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtrqwnaofd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtpjgebpsv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtoavwpdqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtnhghmphn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtodrpteif.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtzfrmgpab.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtfdsqilqq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtmbmnniam.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtzvubibqb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiqffxyo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtyywtlqiy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtyqmyxsxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtybdoxppf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtsvmvmtni.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtuytpjnyz.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtndmfeaoh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtbmkhjkwd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtgedtvfsm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gthfaeaism.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtdupacote.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtkaiiwnte.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzshnxmq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtdvxakvml.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqxlljoov.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gttbvhaddj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtuemshzuw.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswbvzxtn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtphgbynuf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtukzwlvfz.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiyseorz.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtngugtezf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gttoxkpcjb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtytkvitnu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtazjnpcxw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtrjeqdkzz.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtnzlkjzqn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gteglviypc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtyrgnygcy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtxxidmapa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtpgzpgqlb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gttojaivbs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gthzvzntge.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtxddpawjs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gthioczzhc.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtjslkqdxh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtjxhjrdgv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtnmjamtzf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtwajiugtx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtlbnmzpgu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtwtcawpzy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtuythxdir.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtibjzeujl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtrhnvnpzl.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtgcdaagov.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gtbvcixgcm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtpgiuosxp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtjygzvdzw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtdxgncyiy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtnaanoqpf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtkxcmhtrx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtwghqdzun.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtbpigftgd.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtopfuczmi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gteksadyax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtzrlamtjo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtxtmvyxjv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtgaengsnb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtsmdfzzek.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtgqnjspht.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtlpyabhcb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtwbeqhhcg.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtyrsrpzbo.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtqwepmowc.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtfiylkjql.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtipsossdi.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtbsryiato.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtgoieeodc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtpjaibqrh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtathqjpjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtaqhuiayx.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtdpvehcta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcgzyqvr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtkmlejxfx.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtxmddvyqq.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtrfzzpvki.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtofzefasw.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gttgdyjstz.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtyaabrjmu.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtfokqgskn.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtkywlzpfy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtbtktuhor.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtfntlbftv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtaeywleek.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtlystvose.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtygnnpbjq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtelxhuenl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtlnborscd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtxnnfzsid.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsmymnfbz.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtrohyfyav.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwlspqyvj.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtycokxhkl.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtiqloeswq.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtvtuiysyg.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gthvuwtlac.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtcrldlnfl.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtmwizhoir.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtrsnzosmv.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtpckzgxfk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtoxkechyk.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtepvvksff.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtahttplgy.html


<!-- 参考信息 -->