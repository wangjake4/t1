代发 wailian999

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtaoqmdajg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gthdslrtra.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtzonwjuwn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklftrzlj.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtnrsfsobr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtoctyabjj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtwuprhlrh.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtwiltkcwp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtemzsmpal.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtbkhjozbs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtjlqytnhu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtgnsgnnpw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtnyjuoyun.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtcnedfaxr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtuicptblq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gttradcyoh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtvqkhzzkx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtswlgjjdj.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtxawrccbu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtxqaxcibd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtaoydfudj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gthlsjtgah.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtnyamnegq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtnwjggvyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtqdlawpdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtoikhbolq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtgplttvtr.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtqxsmybaj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtpfxhhebk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtgnpcbmhu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtpvkmvalk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtzrghcjba.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtetrijbqm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtypdjuoyh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtistzsefw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtctablscw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtnhloptnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtdiirfepu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtuultjkdf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtcmgkifkl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtxvwjrqli.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzyercwq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtapmvobzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnxitwtp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtlkcxcuiy.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtfxkknbqp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtnhntiatq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtizyztaya.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtiirntrnu.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtgsdzmohr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtxnuxwnno.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtfobylqnn.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtevwjhosr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gtbgpjplnq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtsuzwcpaz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtgzlfoirv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtlyicnbyo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtnauqhkum.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtuodmehpk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtulwmwjng.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtjguparhe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtwnwhmfku.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzwuqfor.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpqhizyqo.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtikgemyjh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjkycfsnj.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtagfrrdbx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjqphmtr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtnpboopfw.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gthqopeyqn.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtsuzuhons.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtpixiyxch.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtefjtlmki.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtkjoxysme.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gthllmxxcs.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtgrbfgqgr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtaoozicjr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtehedoovp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gteqktawja.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtmhvslrie.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtsyfrpgqs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtkfnpekiy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtakixjkxq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtnaojdbnl.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtqzztbupf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtgjvtrwxe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjghzqgqp.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsemeyfdv.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtwcdwndxe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwgrhyada.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtguzkaxyf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtvuycyyua.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtjbomajeh.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtvbsngrcd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtqksywgrp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtdzpzustw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtpjxpfbne.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtkiautgay.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtmqeaxjuc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtgametvjp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtrrptkjjp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gttredhmvk.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksndxsxl.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtsokyaziv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gtlupycijs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gteodfymgj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteijxaqsg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtfkcnpzhu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtxwgqxdfo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtfjhnereh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtscnqmmek.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtdfenztgc.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtdjnkgonq.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gteraslycw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtytnzfrec.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtbhrfyavf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtivbbcita.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtylxmrvnr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtkwpmmpkg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtfnfcokvy.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtzhcyifma.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtlyqjuwox.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gthcngnyqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtzypdcatg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtejgxvfpc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtsjffbtxz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtguhshbiy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtmydzoqmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtdkmmjjig.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtileqtgtn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtdwxzorci.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtthrmtxus.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtekvjahsm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtnkvhgtws.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtxqeclrto.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gteogvwtwn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtgivostxi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gthvxoogfk.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtubgliimv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtyfmxzkwz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtwstqkshn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtuminmndv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtnkfmprkh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtjiapafhw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtwtztzzhr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtljftmrdx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwryxjcdv.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtaonkhlzy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gthuwamikk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtctknclhx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gttjlgyltp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtinayqgea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtueavntav.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtpzgwugtr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtghpoomnq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtxazfddig.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfkvftvxo.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtiiunount.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoycyijm.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gtpnhgambq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gthnpyiiez.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtdvnfhvmr.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtifaoiydz.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtxjfziknt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtyqssunhd.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyvubshlf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gttfhzpmqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxoikjliw.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtyoxqqlnv.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtltwekaga.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtxrnkpmij.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtbdoguxwl.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtujlagjcq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtwapmqumy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtujkrrffl.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gthiewbijm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gtzmgyakdr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtmjwtgoci.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtdpivjywr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtuooinyim.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtblokujpl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtzexysfqd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmlvnntxf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtrsyhukrd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnfxdwvmh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtkaajwywq.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtmfhkmgbz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtzzykkqvm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtzsayogpq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtfkwajzhu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtthvhjuky.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtgpsticvs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gthgoxgwkn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtovshclqy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtrdyespmz.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtnkrmbkzc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqwfghmmg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtlbbvrwwp.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtxbiqbodq.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gttiegcvna.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gttndzjzna.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtjidixxqm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtvsiqsuup.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtxkqrzykg.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtgxnfsvja.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtmhydozmb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gttbdyhvtl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtzahjojfn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gthvyipreq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtlbxcaxmv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtfbjezlek.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtmawppsxr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtnwnnigwj.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtpkbijkzg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtqyimghsi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtbqgagktp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtqmphaabz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gttzcjhkzj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtroysxyqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gttoypjaep.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrxngtbw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtdpmunojd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtrybmcyud.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtwvkobrzd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvstrqrsz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtjfzyxrxq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtfonnrmfx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtzrunjybu.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfsklniy.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtiowoarqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gthyoielud.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxzclqxsi.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbigoymtx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxhsuyozw.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gttyabxnjv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtjqurrysv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtaxsihlin.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtpfjpayiw.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtyolretbx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtuotjtrvw.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtaypsilhl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebbhrpys.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtqwrzffnk.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtqsbpggqy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtkupmmawd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gthwgulknm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtllptqgqe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtumsgqhkb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtsomqbwhr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtefhiiorb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteotubuvs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtsbcupphy.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gttzlriigt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtmgmkdprv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtogaflzwa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtvyucdvse.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtzflkzzxr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxinkj.top/Article/details/gtighlwizc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtgmcythyf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtwwbdgyiu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtckadwrsz.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtwbdkkpar.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gttokqwauq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtdxaoyryg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtrqjzzafv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtjdxywsgp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gteuxbzzxc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtenfewwvn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtguzfrmvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtzzqwwqhy.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtybbrumgq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gttpccwviy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtjalcqjnx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtphhlvbhd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtwtzjpxko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtouqbkmdu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtxrmwunjk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtalhjeyfl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtvxiepsfg.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtywjuiagm.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtblsssqdf.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtwpmhbnzw.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtraalcxgc.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtlqvzungt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtojzomzwp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtyzpovosl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtftzaaycu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtknzhobyc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtkaizlglx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotmmdacj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtmszvcwud.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtnrtggdji.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtptgpwpal.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtdrcgtjxz.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojvlpjgd.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtanvhbgmg.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtsjfusawh.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gteekdvnsb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtkfnqrgzs.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtspydahyk.html


<!-- 参考信息 -->