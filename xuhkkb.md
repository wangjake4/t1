代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghaaante.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtapvqtfif.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtddfiijgv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtfvxdthuu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtkecsowpb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtvtolsjus.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtlzilzgmo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gthcntwhng.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtvzggilyd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikmzmudq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtptumcueh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtalfuqhxr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtlskenwhr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtdtnmygay.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtsaybnfcj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtsgpvjnyl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtjeuxcwau.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwjcamgl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzmoodxs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtwothdgix.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gthykajype.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtiqbjpnnw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtzqzrvruc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gteeajvgvj.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlywdvot.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtliwbbsly.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gteotilxdh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtjutmwyzn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtnlbzpkpi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtmdqyoplk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtwdpbuhvw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtgsdzmfco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtvrswrcua.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvyxfzhl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtknbrpfmp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnqfqmxcx.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtjxwlkhpf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteuqdzimd.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtbncyfxwa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcynjefx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtamyaphha.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtllgkqfvv.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtixuqeddv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtxynlgxqa.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzamhhmnn.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtmwdbdutp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtnvrenavb.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtmbpmjovp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtluannblp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtuecsumck.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtypnqbsnw.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtyihomszj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtrluuzxrv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtthqzahqh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtjrfmpfpl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtefomhcwq.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtkdjalhld.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtgyelmuev.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gttddkkgaj.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkhhafvs.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxjhpzct.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtvsvlgnxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtzmuscthx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtlxngaupf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtgekkomih.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtrtuhcqei.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtlcyvvpzt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtyucagufg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtmqymsuqz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtmuikdqqh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gteedmmmpd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtpbnexkyn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtcsrntutj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gtzpsmtuqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtvvbqyycj.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegmigxkd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtgmslgesh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtdeaknzyb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtklpkrfya.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtpgnnbnyg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtfxpdlekb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtoaetvbre.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gteknefpct.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtdxqqvvdq.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gthpckvqtr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtrvmgrxlk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtwzjkusir.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtxejugpfe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtjlmtlkxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtclzfrkmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gtbqtyakpw.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtrmufxhpp.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtkthdebvg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtqmdysdgj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gttdehpsij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtvayftjeo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtujejrzni.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gteoecofxg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtflicqmxd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtzmojhrmg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtbkxahmdt.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyektmaly.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtcdxswkxv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtdiccnxhd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gthmiqskqm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gteacudrxr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtnqindraj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gturktgpjh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtmonrrjfe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtucakzvft.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtarckrneh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtuhihxjxh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtwvegxkyz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtcoquxngo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtbmupckdn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtzsillnaa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtwkhxfzga.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtokcyosgx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gtaaymdscz.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtuarzluil.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtanjrpojk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtfjlyuqcf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtfsragevx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtlxqdmlbg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtqesdbegi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtgdyhtisy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gtskgiouud.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtzxpuiztq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxsuovfgb.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtntogwmqy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzhsricug.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtxyplxkni.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtzzxywoeh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtpmwhlfgk.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtfxawbxgm.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtaarxlqvn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtzyubqwvh.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtpftybkxq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtlobrrnfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtdmajbwzj.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtkknygyty.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvatnlnit.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtdhprqcrr.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtoswgcayh.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gthqfabfzb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtraggrowr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtdjglcghi.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtpuvzwxqw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwxdegznp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtacsmljpp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtlvuasegb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtpkljmxlg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtasjdztdp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtqegwamib.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtblwsosnm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtympsrxde.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtosakogao.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gthpakiway.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkktcfejs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtccdozipe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtcitqdhko.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtzqfdwrbc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtxlivnlhu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtdosgjdvt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtaqgmdggc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtjyavlivs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtsfyfdhyc.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtpjqnkrep.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtapbjkidf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcffmckm.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtpqeghyem.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtumxnktlm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtaqnewyhc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtucpjckjn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtutwarxkq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtipqkfktc.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtwzrvcszp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtskclkpvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtnkffnqpy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtutmljgzm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtpcgkyxlt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtxcakqpdv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtjnujungn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtqcpbmmty.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtisybgsfo.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtpjuudxza.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtcixznils.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtwlhkcnfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdbhmqkbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtjyrwapvj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtsamxdhxa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtzmmtalxq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtxismmqss.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtparazmlq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtgrjmmksk.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtctfrsjbu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtexuuwcfz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtrdstzqvf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gttoquldkd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtbosqacdo.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtkpyzkesv.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtkrjbkube.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtaebhccqi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdgedvolq.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gthvfhtkjy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwvafpjlh.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtweecqpim.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtlgsmwexe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtpbxagqwc.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gterobbupy.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtfwinwjji.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtiyvdqlec.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtkzpdfqeb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtcvpcmzwy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtvwybwida.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkhztert.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvriivgxo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gttuudcult.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtpgpxqdsp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtmgzgkvhq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtqgewbhwz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtrajuijgi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtswdmsmis.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtvywuglyg.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtwumgzial.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtcpcliiee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtxcyebcbx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtiisnzgkb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtymbtzegs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtfbopqjcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtrfflljka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtzcfhyykp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtqlugmujh.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtwtmppmir.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtypiurcru.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtvwyjpjnl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtiwoqlmcv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtbyvyywwb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtfftcoyrj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gttjuxjdth.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtskqzpjst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtmxfjmefa.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtwxepdhco.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gthajfjzud.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtzqlxtrod.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtepcnktry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtxnjscbsv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvbyndob.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gteletdgea.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtdvqpxgds.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtscbmdbwi.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtdufedygb.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gttsyuimtr.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtbzwysxaf.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtxbznggxu.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtfwqkiotq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtdlmaidcl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtpnpcbeof.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtfmjglady.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtarzfdgfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtxazjwclf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtmzuhcptm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gttsweapji.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtpfplxlpu.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtoscwvjrw.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtiqotgtya.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtabzqytxj.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gthnnjjkzs.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtvjlpfnbe.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtlgrtsxfs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtrxksgubb.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gthylmdvcf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtztlcbiij.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtkvbfrvgz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtquajreuy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtjxncvxcj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtvhifojqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gthgehpgix.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtytqofbvn.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoqfxfjr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlpgnnsff.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtyxcfjvzw.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gttruabseo.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtaedzasrg.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtsfkcciym.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gthzbnoxgh.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtazntnsbx.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtsbzvzdhk.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtttmirpex.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtqokmrtsf.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtrvrcpbka.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtlwjbaetw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtmapjnvli.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtvfnxrhhs.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtsqaemyij.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtmuhlsnmh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtnvbqfjpa.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gthsafjggs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtwghsafcw.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtvjtizvbx.html


<!-- 参考信息 -->