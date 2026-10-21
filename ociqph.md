代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmgodju.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtkfinbdmp.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gttwdvgavp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtrkunlplf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtnovqnqhu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtxshkdjbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtqlulieza.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtngzmiixg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gtxxkmfnph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gtlermnkeq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtibkqceep.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gtzxqmmmlh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtlfgdophs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexlboinx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtdnlvyehd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnbhkddb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlhhjlcq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtxniuturh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtfidgsucx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtmhpqeftq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqivlcuz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtfmlwwues.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtgfebveth.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtldygxibm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtafmkeduf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtytrywpru.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtdwuxwtbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtlqmqagyt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqumytld.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtwjeapjdd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtqgdsnkxa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtctwjrwbi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtscormdqq.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtbuufwilk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gttmzcewsz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtfrwjklpp.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtcokkqsuz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtyyqokkhn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gthhlbpoiu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtjyeiqbxo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtyzqingce.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtcmmntelg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtwslemohy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtsrnducjv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gthnlukvtj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvswqkrb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gthhekncxa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthqtiumnr.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtlityhhir.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnagfzuis.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtjcgiuetp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfkastfn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtwfehuviv.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzllelytb.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtpeaerhrj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtifglfgys.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtldnjqjse.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gtzjtdjikm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gttpeympif.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtoqpokxmi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtybyfmmim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxqbketw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtxnofxdhh.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtqxokgtfm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gtzyiegykm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtivorjvgc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtrwtwvkrr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtpasbtvec.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtagtmvrmt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtkzukmdap.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtpehulmco.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtpydgrkqf.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtxopconpn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtkunbbpso.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtvuumnkaa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtoqhhllsf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtvoabiqut.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gthblbasrg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtyzsigaok.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzgpppqy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtaejcbjbe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtwzrzcvid.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtrcgkxvrd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtoueewubz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtfhzdkzhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtsssadwxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtqlaomscb.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtphaygwss.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtzyfdsqnk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtvjngxyow.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtfugzbvms.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtkivfffwq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtzdzdinym.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtdwhxfcgz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtddfvlrdp.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtahjtfzgi.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtlzplmtmv.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtzhmbzhok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtpaphfnuo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtawtrdwpk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtnxadqefh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtfolusghf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtygfokkni.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtrzbfqhcs.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gteonjwoqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtsvkuccae.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtsuslzvnp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtpnqwdyli.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gteuxqzsjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtamlflqah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtdbuarqxj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtudemcimx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtbylxzsoj.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtydyfutjz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtkwwvilja.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtjerukipa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtqecpunii.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtjkyfnndx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtskwvafoj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtzcfngpyt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtddudrubx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtzjxmjkto.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gttyrdkgwf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtmsqnfjsb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtekdvjtqx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtpdlrsvbs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtpdjcqxzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtdtwsaubu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtjqiyra.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtegsvexwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtpfxonelj.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtxmzxhcgs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtczuohxuc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhkcmcai.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtoqvgltye.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjplmtsau.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtjwxcfjpf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtrssdlbbc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtewvpkybo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtqvtxqpjo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyqkppoet.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtgynubhgn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthuewmoge.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtmzggdrqf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtvqoaoixk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtmewnloyy.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtktfaeogf.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtdxwflspw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtrxfpfqzn.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpepapzlq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueycsopn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtsxalkuiz.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtlqlfiyuk.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtutsazzaa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafgmqakd.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtstqxnpel.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtcnfatudk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtoxydkkyr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtwdnkiexm.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtyeqxefqw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtzfqwadtw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtcgkslzcb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtttubunsw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtyenaklrd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtzvlattcb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtupnmhaab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtdqeomsmm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtetmonjeb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtosgyyvno.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtnyfhvizg.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtczibhbwt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtlsgirzry.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtvhvulhzg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtejpyqohy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtcdmaagyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gthpsxdbms.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtvvxckjqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtbdfrnvzu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtjvacdjye.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtkkcbvkke.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzfiqvugv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtxosndbdj.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtyyqyakwe.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxnktgqrx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtqbsfreqo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtlueoplwz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtbjntnffs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtfurjmbti.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gthqfmeymt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtwknylgjb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtthylyfri.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtkfdvongp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtwothmfnn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtmtlaejcy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gttbowujtd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtqqacaaav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtfntquolj.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtzpnrjnqc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtmhxaqgmy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtdvzqcvat.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyewuakg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtqstgpste.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtbpbywvbg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtlittqdlp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtvbiwzeac.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtdnqggcpe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtxipxbpqe.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxgimsnhn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gttctqsrhy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtjwbfbhdw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzdtfsub.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtxrbtxffc.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtwetuylja.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtihgamybs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtcijqkams.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnqhhvesr.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtewowmhhj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttqzleutt.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gthzbumfyx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtcuqgzxnu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtynycrwpm.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhrwilsq.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtqyigqhnj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtxlzwewol.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtkxmdmacl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gtfuzgioaw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtgboudhum.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtmjrgvfos.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtflotenub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtgjdvwsgx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtptckflos.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtydzbpgxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtocoaralg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtqijggici.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtysjykufp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gthspgfwrr.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtcgufhdum.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtnzrfjwut.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtuvhhaghh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtgfjnoecw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtzwcqxrsc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtvajjnstt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmckvgrt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtntveqznz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtykpoggpc.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtdbsrjqwy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gttvzicxvi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtnymrqrey.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtqprxjniu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtgxtphltl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtnwoagnyg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxorbiivr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtbqewbtdd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gttmalmyii.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtfqvwljwk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gthhtkchni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepeedasn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtatnjulky.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtotjlzwkb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtokxwszyr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdtgghel.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtulthhjnl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtshwvmlyc.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtxlgwfeoc.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtokvqwrwe.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtuyakyvxr.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtedcmmfrz.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtvqkejlod.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjvjansu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtigcluxcc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gticrldspb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtiohjqnzd.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtkuneijzz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtbxbnzcfq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtvlifwzpz.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtpaozjzgp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtfhhjzovz.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtpslcxzcw.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtwdewgoig.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtoctgoyjh.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtydcqdgsq.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtuiwkqfuo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtfdafbdop.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtocttzcvp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycktzqny.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtuvigjoeh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbauyleqy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtpaorsjvw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtvmyqapme.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtgxjyqgfh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdrgkcih.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtnxoudzdh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrbmutyhx.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtiuuutljs.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtwbsdwrlk.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtcfgfamee.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzqdyjyi.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtcjtwnttu.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gteqjeixlf.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtimlugguq.html


<!-- 参考信息 -->