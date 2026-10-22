代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gteujjbqes.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtytglmhgi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtjugmunhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtyiguzmwl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtatdcteij.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gtscwxfskl.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtrzywyddf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtsvssjfrh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtporrnqbs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtduxkhfld.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtrstztwqv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtipxnbbrt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gttszpwlhq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzewcuvbl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtchbsgkmf.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtejzmlnhg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gtwbomwqev.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtxqdtngne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtojhqlnge.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gteexcjhox.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtslnokpbn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtenriiagy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtwxnhnogb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gtxbovpvia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtxdebppbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtvvgqmiyc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtxxslwvdt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gttplrbjuu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtyqirhbrd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtsttqxmdu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtyaqockry.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtgzpgwdes.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtcyhrglhw.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtptfrozyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtocaemvgn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gteqqqefgl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtnoleuvbt.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtupagwnfm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtqgctmysn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnakjdlx.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtqxenuvqv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtzkibbevf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gteedeixro.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtckgxcsza.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtalhsslmm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtnfgevdfd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssvejkyt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtnpnlpdyc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gttkvrwhzg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtdbvbwirf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gteyogbpkg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfymvmjjp.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtyvjaevpf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgwpuughv.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtpuhbpqvz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtnufvpgeg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtmvgzyemy.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtikrfcvpy.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtvcbhrsks.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtkhzvsqpr.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gticfgnybb.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtvfxaumnq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtjymvjhet.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtakfahinl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtzaispxjh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczfdgjlf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtstshnujr.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtzbxrzltr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtanrdkybb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtzujjicqp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtvatygbrg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtsjrsaaln.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtyuhfnudk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtwgakjfnt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtsxghdryy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtrnwfelxg.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtujifcgch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbnxztmys.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtwwkhszaj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtcjpjezcr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtdknjkmqg.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwedclsdq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gticctuspq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebkeovwi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtbqgresrg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gteerhrspw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtzqfugnno.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtuawccsnx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtkzfiwkka.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtkeofansp.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtbllurqyv.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtfpwkmoxy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtuzlfeuyl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntgcgdnh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtzacezzzs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtvjfgwqtw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtoyhbcazg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtiyccypse.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmidirgdy.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gttdzydzpg.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtbivjmxqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtmnwlaqgy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtzrdcereg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtoxqoudfk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtyfdskipd.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtpelreopm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtwmxlagyz.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtepkhqecg.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtqoptfkyx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtbloivekj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtidwuvrmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtghoibois.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtvqdtjuft.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gthasuttwi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtxszwfzmg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtwarzrsvm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtaokxfzwu.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtyqemedsc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gthilqzkbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtigxbrhlq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtnzdfxdkg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtzhcsepul.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtyyutgbet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gtmzkcgrbv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtkeqgqrjh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtghocbuwd.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtdyrgwzcm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtdxhlsfat.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtafvaylxf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsyrhvhh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtfhlaliqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtrpgzdijd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtifbhsqfc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtrdoaqaex.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtslmgzxwx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtpgrrqyef.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtubcztebg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtquxrbola.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtxeruozji.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtuqevparr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtkasezhku.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtrgkbefrw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtujwyehsr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtzzcqjjqy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtydnrayyz.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtqfvbmwhd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzzdtqfgk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtdgygzpet.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtkdygvfkm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtmdvspbgf.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtuuteniko.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqbannodn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtvzlmiaug.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gttmmfmvxy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtnmvocvpm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtonxvawjc.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtteievung.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasygjuwa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtfxxkpsha.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpzofuvry.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtgspdvbce.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtczsnfnho.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gthznmvrwx.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtvoijujfx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtsqgqbijn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtlmtwdsex.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtqcfieiwu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtrzvyxlya.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtazeunogd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtntzrzfhy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtltdjyvjb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtbqxyxjnm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgeyyasu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtvxmwuiyo.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtinxmuotj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtndnkylez.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gttqisdasv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtzoamimaf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtekbiwsir.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gthhldjebf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtmcxohdzb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtdnhjhptc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtitxnxhgz.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtvkgcracf.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtaeswuciw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtacbudmny.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtujffktad.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtzmwtswin.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtqzxfatao.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtyatjdfui.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtcnfrfzvi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtpueoacgq.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyacsyvxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtgbfnqnta.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtcrooyzyy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtzedqdxwp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtndqqxbcm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtmfzhirzu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtyonsvwrd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtxfotgeea.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtzznkeuvj.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtlyxsitqp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtifbzntzn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtreztcpmg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtjnheetsm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gttfgjbewi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gteawyfsaa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtekwtkwst.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gtjahhlswp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtogvzryzo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtpceykjvo.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtrpkmuead.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtqzwcinmm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtqacozjdy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtrafylvjf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gthpxnocdf.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtberfaocg.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtyvsaopxy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtyyoiszws.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdmnoomtu.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtfgcosynj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdkwumbjm.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtbrbifoam.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtryioscmk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gttqgbgxze.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtcyiaawpc.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtalvzwypw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtdwilijtm.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtwvgxavwu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gttmungxwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtabirujfs.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtxuwofszd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtyarjjtdx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtsylozxmz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtcqdovmmk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtaavqgmrb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtqdsyxrwm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtphpeyics.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtqxzqyqrp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmkynycsh.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gttupfnddm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtksmxkeqm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtwedkirwj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtjdvftqiz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtjwihjgec.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtedqgjage.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtmpzklqus.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtlaqglrxy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtnxpiygho.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtvgnghdpb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtxuonkyms.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtihhretgb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtbnnbumzh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtgserpjwo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtgtpedhog.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtyfkundsl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtnzhvqpfv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgctlihng.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtbkisvqmx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtjqlmderk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtkiwqiycx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtssjbpvmn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtmssotkci.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtwuueodzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtbgifuqgo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gtakudirso.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtjdlbfcwk.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtirsbewiu.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtzbffjlak.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtqmzgcvpz.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtldphakek.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclihilow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gttjbeyxzn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gttqlfxflu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtvcnnfnir.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtdrwjrzxt.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtbrcdpvmk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtwnukclqh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtndiqjxmh.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtxejtuzck.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtsftymoxv.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtqjsimpwa.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtpskywnfg.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtdkpspbkj.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtstfmbnux.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtzrfnzhcb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtwjgpajnp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihmkgxys.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtqfdevbwy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtlyvnnisd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtlbjksasx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtgdztwbpb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtgeoecpws.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gthxhspwvs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttmjrkgpx.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtrvgzapwv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthnohulqs.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtroqurjah.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiksrbnp.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtwlinttch.html


<!-- 参考信息 -->