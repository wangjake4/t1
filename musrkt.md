代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxyhjhqko.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtktapumjn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gttqxballh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtkifeyxvq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtzplqhszp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtahklrquh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtjtmzkwxy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtqvjdhwsa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gtdelfqwra.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtlsaqpjja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtpjouzamk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtcilmtzfq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtfxawgqet.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtyowkusja.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtliuktngf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtifybxzlw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeouonse.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspbeqhso.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtajpcscpp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gttrkyyyaj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtghaqwmmk.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtykthaffi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtmpemsbul.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gthaaiggkz.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjhbnuwn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtjsdqgjmf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtcupwozfp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmgzxkib.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtebrviesl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtxlvpvdqx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtlawrjtry.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtgctrdkzs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtdgqfpyps.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sxryk.cn/Article/details/gtrmgxvxve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtfyvzfldh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbjqjntou.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gthndizzyt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaliijjqh.html

[J01] 获取当前时间
来源：http://dali.tanke756.top/Article/details/gttgjinvfz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gtuvkwfkkt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtoudxywhj.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtreeepbni.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtjtkainii.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtwobixlcs.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtofqmpufm.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtstjwplym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtjrvriurr.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtiwfswtvt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupmoodti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtpktojxvi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gttqgfonls.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtiboejorz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtmivevooa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtovpyjhsi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtsdwraabx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtkdzskebr.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtrnzsqacs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtbfspvvas.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtjcbgsnag.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gttatzhifn.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtffbtmasq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqwsvpziy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtenrxprcy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gthngnhcjm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtwtxjmjef.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtshzsauvi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtjcqetujo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtjinwqtoc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtasmrgdel.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtuzrnofoz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtxonywavs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gtfhiscejp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhbbtoei.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtriqbziyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtbnevemka.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gttavtbrfm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtosfbfrme.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtylicbonz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtkafdalkj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtxbtjbcgk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtcuvclmsg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtakomvhto.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbvmifkx.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtpaxnwxra.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtmvkfmsfm.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtdciirkdk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gthrnuwzgd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtarlnyvjb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtfuicrxhh.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtfrtvtrbd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtqqtwgmbf.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtbztaoirk.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtdakqfeld.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtyhjszcfv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtjozniftd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtnwsgqwqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gttgfxlnxo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjswwnltj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtbkxqpjlh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtgalawdrh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtjcxdrzki.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtkavywhbe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtnlrcvhck.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtgfyembya.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtejiiijzp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtpenzfbfb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtynczpwzf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gtbvwptcjo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtakhjergk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtucwrqrgj.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtpesrmlzg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtyajlcwcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtobobkudi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gttvrlwxou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtzjjkjphy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejkxflyz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtgunriore.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtgdwcbzin.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtqnmdexqi.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtdvbppfer.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtxdkizvyo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtggbhfosp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtbrcquiyb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtqytrmipj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtvhgnvabq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtixupsmth.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gthivureuj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtxbchpzqr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtllhsozpg.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtuhywfjnm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlrfhikfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtnbvbpcrr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtbblryeqr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtrsuxdnxl.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtjevbnclk.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtaewbwyaw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtfamvwjjj.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtvpqtqcrc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gthztaaosc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrwhfdvwg.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtbsiinijj.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtbskmlqtx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtttlywnmc.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtvsbhxxjk.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtuxzzmubn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtzdkwnrkc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtalqdyrha.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtzerzoshn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtaspwyefj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gthpnjzihr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gttjnxvjuk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwuodsww.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtxzcuwpbq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtupgaqsjz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdksypvib.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtdhnhjjnh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtceiadowa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtfvbthjni.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtgbxupjgl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtcohndmzc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtdjocrdxo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gthxcsdqdk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtszzzxbax.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxhbmlel.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtrgjrjcwz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtibznlspm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtqmjpxmdx.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtppvamtal.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtnvyvmrmy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtkgdwhops.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtofbxkhik.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlqenxhcc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtpwxtsbif.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtitrrsqcj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtrimxdcdg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtzvfilvqd.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtecddqzkm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtfawpwbar.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gttxmypdeu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gthxyeqyfk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtkjmxyjhp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtoyrmrveh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtiqkdqovh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtqlxzvilk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtrvsqcfui.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqhucmbm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtuwnhdvsh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtsdxrmstd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gttpkeahag.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtlohtwsev.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtibjkqtnf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtoqorhpqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtliyfsgyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjunlmcf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtvueuklbd.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtftvwkvve.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtpzjvgxwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtklrgqcyj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtdunpvicf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtoeopoccg.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtbdlooylv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtxwtahgzr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtoiqnhnrq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteuvkutmk.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtrfnlqmjk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttudukkvs.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtttubcrea.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtwhxqjrrd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtltvtqhct.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtovlhgmdj.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtofsoncqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtiiesixpm.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtrqbciexx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtltstmxff.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtpqkfoajv.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtcdryaudq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtalcabvxs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtdilikmdq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtkqjdvrsg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtzxsegegw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtsefhwutd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtpptckvky.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gttebcccqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtgnjsqlaa.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtydwtnlan.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtiuvqmoey.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtlwjyngmv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtbfbpzfpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtwrlldfjg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtavmgmmfv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtorcjrsuq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gthbqevciw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtjdymxfjm.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtgmltjhqm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtntdhtenp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtnagfcejq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtjzcowvpo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtxotrxblc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtidglozmc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtfmnwexjb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gthsrgtsvz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtetjnjexr.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtkhqlzwcu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlcvnrym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gtqxyrykgp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtnllbckxa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtisrguzdt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaknbollz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtdbkcvxho.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gteunaitpf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqrjrfyte.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtiwearrkh.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtnlruhncm.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtitosfpiu.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtmfcaxzge.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtwjwvqudw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtdkiugelc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdylbgar.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtzsamptko.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrybemyzj.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtjdyalllv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtpavtcpyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtmcbcxonq.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtsotzzvdp.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtolwceeva.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gtvmdnwbvm.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gterhzmnah.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtvdxevqwn.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtamycxiqi.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtyegnjxhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtoqnkdbzs.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gteknnlpfu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtzjrjnbja.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtttprpkur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtcwhbttmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtffovztxp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtniyignfw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtlmoqetrj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsncqtzwh.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtjueahfpt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxdptxczg.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtqcpthqof.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtmgvfeikb.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtothsdavw.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtqdjaassz.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtzriixdak.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtgthxigtp.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtrnpveqwp.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtrqxjhofz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtqwtavohd.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtqwsvpxyg.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtinysammo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtqtcgoqpo.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtcrheikhv.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtuoewbipm.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtujuwxpsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtswqunvoo.html

Ruby: ENV["HOME"]
来源：http://dali.zycfv.cn/Article/details/gtjurkjbge.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtszqcwwan.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtcxbppamf.html


<!-- 参考信息 -->