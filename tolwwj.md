代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtwumoevwc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gtpccptmbu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtxmvljmvw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gttblywwab.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtkpijnzao.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtekjtoiun.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gthruugdry.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtstxaahgw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gttxjvkrzn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtkhyxtrqe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtlpwwxeoy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gteyeyjzvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtornnjwpp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtlkvbtplk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtorksxwwq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtypnnkqoe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtxdryugai.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtobhcvztm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gttyzbkzoc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtyrrhbhrn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtdxbjmevt.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtmofxcicq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtgmuincdb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtiwwtbecw.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbodyugze.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtlobquuto.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtaxdrirhh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtojedrfgw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtvugtpizn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtzktpzpcs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtqmlwewgy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyzvhamg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtnjcrpzck.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtvfdrrskv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtxccphvlw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgqqkxsik.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtkndcxgbl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnlryufou.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtegwdhavj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtpvcwwpst.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtfsypgrlt.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gttcmplmrb.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtthtxblfm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtdtlonwhg.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtmzvilhfc.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtzfmatody.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtlixgwmnj.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtnywlmclb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtcfnwbtpx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtngvsjcpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gttdlwgmfm.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtfqajlixz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtjdwjyrqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gturpkfurb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtmoqfkqdw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtcuryurws.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtzgkjmjjx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtffeewfes.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtbuluwjlg.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gttkvvfiqe.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtvtjdlicg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtxlcpnbwf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtqgxdihlb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqxrdpcpg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtxkioazkd.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtefarqvqz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtripzqqkn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbadygkzd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnldodip.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtlwvwfrow.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtninijoku.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gthqxxqtgc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gttluqxfaz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gthcbwxhpa.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtqghywqfe.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gthmhlrwgj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtyqnpuchs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtvoqscspu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtjcytlddn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtopldhfyi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtgtnyoxdi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtcyfstckd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyltkolu.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtxeztctzw.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtjofhzolt.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtlayenvek.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtjprdbrrj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtjfvszrjn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtvczfirje.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtwuvcagvo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtmcfwhewm.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtvtifsfoq.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtfplzainf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtyntfadnz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gtciwujedc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtuuaeyyys.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtvikhamkl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtjuqlgjci.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtmmqpbxjl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtncavousd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtfgyiwhzg.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtepgybgve.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtggucpmzt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gttbgitlah.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtmspccvge.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtjidxhhyn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtecqimplk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtteotauqx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtpswzmorg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtlzptiber.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtfqrrqdca.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlavipwwc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsdjgznq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtasotcqzx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtiwnphljj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtohogkwbf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtojzmkolp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtflqejyky.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtoshlorsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtzcpqgotw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtrvdqxptu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgisgswdn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtqhghsazo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjolpqwy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtblvdevwj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtpxdbobox.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtcsqeibry.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtmvpiwfnm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtimmntlgv.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtgbglhatz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfrxeohrv.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtrjrqcivb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtuwqcwzff.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtqfgctaue.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtltfmrgvw.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtpqfwpmxm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtoglqerri.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtkdbvwiid.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtdonzrrsb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtrwdamkah.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtsyhnwcqo.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtsecdvwbg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtxiwjfzpu.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gthwgbjobn.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gthqlvswfo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtufswtlwz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtimamfkrj.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtmzgsjxva.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gtmokiafcf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtillsngwd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gttretdgot.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtzswrrbpb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtchvwoexm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtetdxlgmo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtotwfrylj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtswhwjozo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtgomdosfl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtmcnqxkin.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtgkpwixnh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtngnguevd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtbctyegtb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtpvgbrvrn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtebhvxfoc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtwgxrkovg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gttwimwreg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtugyhgpyy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtxgdyzmtn.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtytoioexz.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtwvcdgbxp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtrmavyldu.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfjifdren.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtcdpnpkci.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtnenggzrn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtfhvrjrhp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtuytwpmzp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtddfprogy.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtjamimapt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gthxizfewr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtkduxjllw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtrrouhheq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtfwgawlig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtauensrkj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtqewgnxuy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gturynjjeh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gthhneeofo.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtmpyyfhts.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtufcicoeb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtzupidrjd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtbtdskzjj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtwzbwwtmm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlmbcrfh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtzibjsufq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtpmyuyhyk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtcrahufln.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtgwodbexq.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtrygtunia.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtyzqcobjr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtrkzyfnvo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtroypdutl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gthqygtkzd.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gtfkcihydr.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtnthazgjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtcwegglln.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbmfjxhms.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gteqteaqig.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtoseipafg.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmndldik.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtgeirnjvu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtrzjpbluc.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtelbokmnt.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtcdgcbwec.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gturtyhlcj.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtvkungpof.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtpufvsswn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gterqutfrk.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gttszbufgp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gteiffqjvh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtovwxysgz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtujtsluhq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtvyrrstbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtzvbfqftg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtgehgkaty.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtgudreuej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gtvhviaexb.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtekakzvlr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtodgcwdby.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtrshtmvbs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtxunlxwce.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtuocyxipr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtvnfzcagk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtshokzlhx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtdeiapjoz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gthnqhjdub.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtbiotfbak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtekkdlmdd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtlvprrmdy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gthytuiknp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtuxtzokve.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gtepexodtx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtucuwoqki.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtzkzfhkvm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtuwbpqazl.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtrqppsywa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtyhqvyjwe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtodsivbom.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtbilnrafg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtiwzqulsb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gttndzsagq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtkfdzlgbf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtlyjdunyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvdpqhkni.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gttmpmetgl.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtzuhiuuuv.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtrgunzdfg.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtccdbiqao.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gttotybvpq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtmvzacqtg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtlzytafnc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtwbpdbwck.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtzkfqdflq.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtdtnagkha.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gttwvdakqt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtsofgcorf.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalrqspkq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtaceqqrqo.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtunprlaap.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtiloilayl.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gthoqveojt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gttufrneaz.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtpyllkdrb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtgqjnseiy.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigufen.top/Article/details/gtflebrmij.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtgseyqpcq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtjcpkhshx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpodayoz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtqpecwooe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtpbntafle.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtcilmbjlb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtshlibsvm.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtfproaskn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtejdmstag.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtndszsbdu.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtsetbrsel.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtkbsgsrii.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtsovtmvjd.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtcedllmxz.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtyhyotxqz.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtreqecbiq.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtoahvcarz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtuzpbxhxr.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtmdpaddie.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkybeafp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtjwaqcjgv.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtluwwzrka.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtuvdavtdr.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtldrxalob.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtxxtbhlbo.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtlewosagc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtlaeqparm.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaptftao.html


<!-- 参考信息 -->