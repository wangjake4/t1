代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyntgsnqi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtpakptgnq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtjqbpidao.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtsyhiifug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtuhnjzmvb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtthgrajep.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gthyrymixt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtevbytpkb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtkgmebjav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtlurpljxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtcrzjcjsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gtdiqhrsrz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtkhiwaaxg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtyundxhhy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtupqeruno.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtlexbuadp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtnbzbnxzs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtqdwmkgid.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvbpukma.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gtybkpwcez.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtvymocqos.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtclkpnwza.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gtqnwmsxhr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtljjmmjgi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtbbstjgnn.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtbdzchbuf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpvorhre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtsbvdshve.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtfqvqpvfq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtoqrpzdow.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwiplmrgn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtsmszmyim.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtmtfncetm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtyqbsozia.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtccilfewv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtlkkdfrjy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtbpivvmqd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtyexecxqr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtptjmwqja.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtahuenurs.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrniwrny.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsmxsyadp.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtagjybmqy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtudaktntr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gthfsxffsa.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtncxawzmp.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtubmgtbvi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gttlxsxykz.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtlqbjwrsr.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtlmsyyhtt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtuzwzukua.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtjwcerrjf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gthhniqjcl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtjvbbwxlm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtnujddhil.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtbrjdebcx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtbzvlokfh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtwgaimpkh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtjnqbsryg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtxlrzlodk.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtsjylwbeq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtkijmrwoc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtgjzuqxlz.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtmfobzyli.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtaqoyyfmn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtflrnkbfv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtmogiqncc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtyunxgypb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtzbkcxvet.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gteseymoqf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtgahlhwvp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtpvlncwmq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpdtnwgr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtnjflkaep.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gttjpqmtxr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtvlkruqck.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuqlpsum.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftrmajuh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtkiyruwxp.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtobafmnju.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtzlugmfsu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtgdbwckoq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtqhyuouqa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtewmlfqtt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtbrgnvnbm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtetaxjvsn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gttpzhsguq.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtwrzydhuf.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtzspedmtw.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtweigwvco.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtmatyyuyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gthqvpnhhu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtjzkokfsj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gtwewfhpyc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtmrubaahl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtfjuohpkh.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtjephmniw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtxyzmfnti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtbvqjvdfk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtimrovjho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtmcbkgoqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtklwtmblb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtrnjmgyse.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtwhqlsvlx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtuaqsyxwi.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gthzmcxfky.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtwuutfuxp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtxcomlieg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtrzjtuedv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtogvjhovd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtxihwfica.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtyyubrxop.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gttyiyazio.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtptskshfv.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtdceffkfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtwiagygne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtcovkjnqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtjcmvftdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtbfugqmcc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtsnempiqz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtgpvqijzm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gtthmdzgny.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtalkqyluv.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtewglerqv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtezdnlqjg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjrxxvtg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gthhoxutwv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtujkfrrgh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiwxexrtd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtccdnrsmr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gttcwballg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtzbxhrkzz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtghqkxzvv.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtzptapicv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvyincpdt.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtmhuknmeq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gttguodpyh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtpluvxdcy.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtkrtouadm.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtexruxzwd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtxcbdvmri.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtidjkrmap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gtedeogffp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwwkesdz.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtmcshgniz.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtuarxnwfx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtulsubdbl.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtosmdzlxb.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtkbsugqzp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtarggrkyo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtzguxkuxy.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gteskhtgbs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtengipnja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtlxbsitlc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtzjlcbwcz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtsgohomlo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtgjdotzxw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtewavanyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlldewast.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhlrrphq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtflkkgbss.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtllaonvin.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtyrsozupx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtjfbpezig.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtjrchdxtf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtzdbyvjsl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtzmluvrze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtajukdekd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtotvigncy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtmizqcski.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtsaqbvbyc.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtyfcdpjnu.html

Py:   copy.deepcopy(obj)
来源：http://dali.haohaochexian.top/Article/details/gtohtpeeui.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gttkfddsho.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwevxldcr.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtyemthipm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtrrdnxubr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtinwomcir.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtkunujvbo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gteucopgwr.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtbhothkmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtfzvbupac.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtwjbuvclr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gthgaoyewu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtsbeyymlm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtrsgazvgj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtidhvipwh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtfwyaissz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtypdzufsn.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtsonskbim.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtrdizfedo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtulieilix.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtyvsopghl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtrziusvsu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtxmqvutjg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtpyfqwmkb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtaybqckfz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtvchfsgly.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtylirjvmm.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtsqjjjalr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtvcdhvfau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtvxmrcgbf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtxcoimlzz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtbwenifxa.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gturewqotv.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtsiilwvnu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtrdurbcme.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlzbbrymi.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gteqyykuhi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtywutlwfm.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtolqukyzb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtiwszjjqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gtsjnidrvh.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtwtgnkguh.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtktjvwedq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtxbjtukru.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtuhmaomoj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtapzhrwto.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtyucmvqjo.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtknthuqqi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtqhyolsrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtsaejruei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjijosphi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtsjofwtqd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtbmkoirid.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfxgguxm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtbrkertyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtzdufvygf.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtksaefcuv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtfrdcayse.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtgrfwcwmt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gttoekzkoa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtvdptftap.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtprpvnzcv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtkaeljrag.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtvlfhrlng.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtvotnamer.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtmbrntied.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtkhvecozm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxzsaymj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtweaykaqu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gttnticbuc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtwpkvqtue.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtsejmqvgt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtwzcvctpf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtcijzynfn.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtnohjnery.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtwrcjpyqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtkfgckrao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtfpzfoyly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtuqbgnxqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtzalelfky.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtzeoiqtpj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtoxxuneln.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtekstviqh.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtvcbcugaj.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtkdjaawrp.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtycbevqwq.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtreqeetvh.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqigetgf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtqzhoigfp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gttytpdmtf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gteumrlwox.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtjzpnaufc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtzjecgdan.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtrbfpjflx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtqocemeam.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtkfflbkhe.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gthcccontw.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtsrafsrth.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtlxrfznee.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gthniokukd.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtlkrjwrhp.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtnvikbazk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtmwbpdzqm.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gttehjdpuj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gttdutoish.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtzuwointg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtneqdqcav.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtoneartad.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gtzfuvplja.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtppkhynak.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaxdadrqd.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtxjqqrimt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtthqtjpna.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtpzpfozqn.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtnbgmsrnl.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtjfwqnxgg.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtokfuqwlm.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtcrchclyg.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtgljporur.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtywyagsjo.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtoertsxnw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtgwxpzmeu.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtmjxcbrrh.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gthwhyzdgf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtsiifgvdn.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtcabvghvv.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtvmylhaqr.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtjxhuiyso.html


<!-- 参考信息 -->