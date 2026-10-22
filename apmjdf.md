代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtirtplkgm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtbgfmcfwp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtevtmxjhv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtpejwxjco.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtvynrgwlj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtyxfofcwu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gttnwzwdiv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtrsfyaovw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtybxisdgs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtxibsrwsd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtnnxvvmxn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtplrpigsl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtwxxwtsyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtetwmyoto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtbcfbcvpr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtitglyufu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtfvasvysv.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtvmfqueaw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtrtfqhqli.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpbcpyiy.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtvzwtoqyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtlkskicco.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccdybpgm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtcnfgpvmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtotxqewbs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gthdpastyc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gthccslhxq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gttkzwvyeg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gttesslpmg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonjnlwyk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gteimijawm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcamlxgzm.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtzahpzxvx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtksuwrbes.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtyzdymjeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtfhiedoif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtrffxxqff.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtiygkhppq.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtlgdkwpgu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtegppkxew.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtyqzyzvrh.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gthmtodqsi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtnxknocui.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtestzueux.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtplyvixyx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzofkkpi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtrifdnioc.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gttlutzknd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtesweprxn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtssoejfka.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmasoriu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtwvzocmfr.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtqssowylk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtdqatvfju.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtfbchdfpi.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtfyfoloma.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtthirpilw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtivwoqxoo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtbyrpepvr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtuxrqbxbi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtwmfyhlgt.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtkdnqloro.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtibkzmgxl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtxpuaixha.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtmiqpjolx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtlizehlqu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtmadjgfjz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdsceqnrl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gtxplywzgu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtnbrbixke.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtgagpqbsc.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtylgiljwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtkfzexjkc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtkwnacjpc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtjvgrecbn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gteohjvkuk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtpfubufqy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtdxuwcgji.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtnlelzvkh.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtavfjtpag.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtwetbjbzr.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gttnlxsukt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtlrrusjxl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtrsbggxsv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtsumznflh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtgvqdgyay.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtbiprymak.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtdcubwhsk.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmbsdkit.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtrzrznrbr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtrxnswpqi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtxlkuuhwz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtaaynduek.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gttedvbdbc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtmzmupptl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtkvhobmhm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtogxbugee.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gttctbjlfh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtlbagxfma.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtquwyzofj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtxmdahimp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtpblhonmu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtcrthcfck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtrqkhaxmk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtfnhlucha.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtxpnxyrgs.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtlixrzpfn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtoeecwjuy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvoansvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtfkkdfkwl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtmioxaiye.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtcafgpeiy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtsrkznsql.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gttvmzbika.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjseobid.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtqnuerytr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtwhdwdgyy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtpzotabov.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtdnmquodn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gteyoxxkfl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtrtjaokhz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtybperejm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtiyhgaxxg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtjrjseygm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzpdjzyuh.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtiatwbqht.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwexnipsm.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtjikuutba.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gthrzalles.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtcesyrfmv.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtmwgooqbh.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttyystvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtldlhjlpf.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjaberylh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrjeclqw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtettaitqv.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtgjcplybj.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtywpwakjw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtrvntiaix.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtckwzcajk.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtahbcxguk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtqkygsojh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtcusijfiw.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlouipwc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtxdmrjpji.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtfelehcpl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtoizrbwiw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtemrkgryh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipbiiftd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfejiucbx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtqwgumspw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtyxntqmup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtxmyofkoi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtgtjpcfmi.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtjuczkjyn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gthuryrggc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtqcsyulqc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtoypjjyfd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtqzhierrb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgeqcfjzn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiabiypw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevfswndy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtiicjmfga.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtzlpcaktg.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtwjkiafii.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtkqrwgvuh.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtfbbvrudh.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtzkwlxyja.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtwpnzlshy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gteojlmcex.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gttryqeapb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtyaodvhpx.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtunrbwlhh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtysxgbbhl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtodghgiwy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtxgqrldwz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpwmxuzv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtxoswvimb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtkijozqss.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtohfqjuvo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtjetlgxua.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtmtyohyfw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtvgxpcxcj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gttmcldbvg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtbmmorley.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gttqgjjchp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtfwhwpsav.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtpomjwxsq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtzqpaqqis.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtzemkwzfi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtavpbdyzn.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtypgfhhfi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtqelzkwqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtvuysengt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtqutqqwsr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtclrrausg.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gttelrtkep.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvhnmetnn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtsuwmtpjb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmfeedjqg.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtxduvvapg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtakldpczx.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtqeddtoww.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtxmtmmwbb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gturrrubqu.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gttopjrrkh.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtfgxczknt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gthrgzbfer.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtmicigwjq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtnrcgvfob.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtbjjlbvfp.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtikgzssru.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtllcasklq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtqjlbbtii.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtxzbpidaq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtjbgztguz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtwvbaxikd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtsufbodcn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yonumen.top/Article/details/gtwqymigwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtpriyvvdb.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtjrxepuew.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gthgmkhjmm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtefkhxujs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtobuxlgvi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtufripmom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtkpyisaih.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtxmhetaae.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtjleaxtoy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtuojszuhc.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtiemrntkt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtzmcyyvkm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtqmnheuaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtfmgknili.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtbtncusxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gthijougqf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtztenlrib.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtadmlvvvn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtbjbrpsdg.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gtwphhyewv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtfeqittkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtvccnomoq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtyksriewk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcarrxkr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gttixxbfze.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtxgsfzife.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtjdgcassa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtpdjbrpdj.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfurqwfzy.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgqnrhxl.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtekwmhgce.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtccgmddar.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtpbsshjyn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gthojpzohv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtaugaesnu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtmewuwdcy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtknoziqgh.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtjordeboc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtrzvoozic.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtmarylzsd.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtxmpnxicz.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtzwmjirqv.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtbqxjpnea.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtfduuowue.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtdyciqzhd.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gttfqpvdvr.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtniaxjokg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtttcjxpfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gtollrfirq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtxijfactq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtexuixiip.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtyaukieeo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtcwpazpmh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtijltevsi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtjeitfmvi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaufntrnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtvwgmkvlt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppqokmgi.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtwhnnwltm.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwaxmjduf.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhmhisaq.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtkzhtorph.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtcmbbsmll.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtdolxcbww.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfadygps.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtwaabuybv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtyovcrwcs.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtzyeyuteh.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtsxdvmaga.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtpwfdwzox.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtphhywnvj.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtrevhjxnl.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtstivyqlx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtykkvqrzw.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtsmwgyknk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtutfsawgc.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtkxsojqjh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxzjgadm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gtjuasxmig.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtpdskrxeg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtraqwxpgo.html


<!-- 参考信息 -->