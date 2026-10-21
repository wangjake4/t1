代发 wailian999

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtkopzdvij.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gthpdvdgep.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtjmzlegjj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtxnlekwyz.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtzqoiqkac.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfactxvkt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtzeitzmkk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtwzsnyslg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtjlcoifco.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtnzxhpxfx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtcslrrpyq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtfwksjkjc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtmhrpedzw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtrvwdymwj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtifurjiiq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtqgjkbken.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtkdzjuznv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtjioyolat.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtreobdabx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gtugnbsvwm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtwqutqegu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtqaictjif.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtlewtwnak.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtmlfccxoc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtpbommuxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtxyzwklzi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtycygudvy.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtazdyjxce.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtwqbercpy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtwtykcbai.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtbuoezkrz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtspwmyevl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtvwijmcoo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqdlyqzmu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtmythcndz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtlgaaybct.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gthpedjfwi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtysedigew.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtpoefgogz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtwdodantb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtecrkbagr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtrdhcvzhz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtipewvelz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtwmlkouyk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtnpdymbjd.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtotfiokwr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtghclkqeu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtenpokcbj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtbubnddmj.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtlwlftnli.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtsmtolwfu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtyvwezozs.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gteztphigy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtqzwxzlkw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtzspupfzy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtpwikxbng.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtguvdcamd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtmzarpkrl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtkrkgafqo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtbmgdlfcd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtwnksofcm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtkxfmrxzr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtdtvzhxeu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmgrxtxkl.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gthhykxdfh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtozghhwwx.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtfxsgymkk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtrbnomena.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtqxlcbzvq.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtgkzdthih.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtdwnjflgf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtuohhvjwr.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gtdgaxfkyo.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtzrjiwisd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtltdoorae.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusvpycsk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtmkhvkyax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtlkqarwcd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriuumhoz.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtrpqtblrj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtxpictxau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtsetzttvs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtxdbjkfch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gthessuxdt.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtlkifgdze.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gthnguxrso.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gtdgcpyfur.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtcuxcwvwr.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtajxjaevp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtfwpwqhbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gteifrkvzq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtbydongzt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtheiymlhh.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtueaumuwf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtgseuerov.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtawtkecbl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtjkrgmrlp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtffrrxdtx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtavuhuegm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtbgdghnle.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtoirdbpcl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtfleevxjt.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfusmedn.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtakqlvlly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtyholoziz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtrlzaqzdy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtlhdepsdu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtpctshhiv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtxixvceli.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gtmpbjhpcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtacdicckp.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtybrrkiuv.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtpauxxvny.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtkrzftxhj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gtfpyoikau.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtlydyttxj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtxgjvahio.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtbbxubipl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtlrgyysit.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtefcmcqcq.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtgfailpxz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtlxdqmhqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtlmkpjoni.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtqpxnhyzl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtmcjeyytp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtgmjofczl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtvfswznva.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtivtobvsb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gttcapmvny.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtzceoeuup.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtlddyscba.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtpuxrlyld.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtyrzaiwwg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtashinskn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtqrwxndnm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtqyhkhrxf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtistimixn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnliqoxh.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtzrzaqcom.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtqcfkoawv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwphfqhym.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtzqvmxskb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtehclvbjb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtptsioslx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtlijoevfq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtitaeojjc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtvrutwont.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtbmfolfvi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtqnzgxbgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtwynrnpvg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtpiemgefg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtqihrfegj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtjcakqgbz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtdzmbrnjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtqenbskue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqlqgaoin.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjwolloom.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gtuzdpladh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtigdqalsw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtggkevqpr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtekmwcrbl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtdtatqpew.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzatzenao.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclumtkyu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtizodxaxp.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtiqmlczex.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtquucztxz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtkviljvhi.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gthjyikyfw.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtfgzsvriq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtoglqjjrz.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtktcupdfz.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gthbdaomeo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtyzpztify.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtvyklgwdm.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbvbqztat.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtfjiiwamj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtczzrbgcw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtlhbtasbe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtjqxsouho.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtpieydozj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvmtojne.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtgpgiywbh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtemlbsxge.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtvetblsue.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtcndulewo.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutakloyf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpmpoyxn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtwnekqyyc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtarxbcnbo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gttrrxjvpg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtvcmhpjiu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtcmottzyc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtxeskczau.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtvfbhqqpf.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtazoeydap.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwibizszv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtarvtmwvt.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtumpcdvsn.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtzpwohgkt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtfgmhdsar.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtfhfgusil.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtegxnyryj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtkyllgvmh.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvlfpkbd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtlomlnwin.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtrrfwpmzt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtzovsalxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gthhbyyfby.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtntyawzvo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtcuksoxvm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtlfrhodxf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtesqxmidd.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtofpxzyft.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtjveoqzba.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtzcczgeis.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtsnhsesqp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtorljyrvt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gttmesnedv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtfzoyahip.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gtgwdvrwad.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkckkcizj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtqfntfznf.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtruyciwpb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gttpdqfbze.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gthhcmuzbi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtewwljlfj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtzsuiqpyh.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtjmrhitgq.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriahrkix.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtexpmczmr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlfwusalp.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtltumzals.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcskaeqjj.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gteermdznl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtctihzxjl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtjqihzqbe.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtgbdxazxh.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gthuwdozvx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtfpvglvyu.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtnmynxhix.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtccbzwzzk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtgupsuxqk.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtxwugsydp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruieygdw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gteeahcvwc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtkmsjqqmy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtcjqkegjb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gttfdrmqhl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gttsvfhfkq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gtqmkfikgz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtbhywwvtv.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtyavbumhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdtjfahc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtrbbopgkm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtorvrajgl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtyhvtvgys.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtfnomuyfm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtchbihrzi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtcmlzwrkz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtiiqusmrq.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtkyuluzel.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtyufjimup.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtmaxmwide.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gthxudyzvt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtrptiugyw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gteiqmxjop.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtpngqvnas.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtylwqtczx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gtocynfqvj.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gthrfrknbw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtepzzfdmo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gtknyillgz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtytokwazy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtjefwoizz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtdekmvmbm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtrqhjplhu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtomrkleuo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtwjltbsyz.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtbhojrtid.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gtehqexkew.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gthnhtcbcd.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtgzekyagm.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtxkgthbij.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtwivumkur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtijixiljs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtbtikcwlp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gtuoqmrwnu.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtojrtwszs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtuhxtrfte.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtwlpygacw.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtvqdfnjco.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtkldpasmi.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gthuxptldy.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtdlbbqarv.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjeuspdx.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtpgjblcvr.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gttnamjgpq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtfpnrbyab.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtxggctwjm.html


<!-- 参考信息 -->