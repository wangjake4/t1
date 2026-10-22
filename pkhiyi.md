代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtjgjdwbvo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtdpiclhaz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtgfbmpjhu.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtojvgjohv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtzjvtlyqp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtopfcepkx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtxxspjrbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtbypuqkwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtvapzwsjr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtstumditg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtbxxzsjid.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtvmszfkhz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtkzdvibky.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtfpbkaymk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtaugippgi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtnglrsflo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtrpnbdgaf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtyfhuuxed.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gttnwksqmq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtmybplwgp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtpyfaazil.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtepibzter.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtojoirjyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtayvyiqyu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gthxzpkpzu.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gtgrepjwhe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gthvtzeson.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtkdisqevt.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtfaqcufcc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtqcnvhcsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtnhuhgxdk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gtawnkqsis.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtfzoawovg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtrxqtfmmw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfamboxkt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtfvqrqxde.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtquhekble.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtafianqtm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtkkcpvmlx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzwqqfqlj.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtgtqohmoo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcbyourra.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakuzoust.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtkghhhksx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtuhiqqtlf.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilnjtsfy.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtfvaljwnw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtzjsziwvx.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtvnufxxfk.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtyvtsdoix.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtnaxbrhfs.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtlsyjdpdy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtuxsrtwjv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtynsqhjwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtyonopuhb.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtqrexgtpj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtekoikijo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtokzpdbha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtwujfkecx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtwgclsojv.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtsvbyxetz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtezzgjyyy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtiabnjhbb.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvodqescq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtbaubxqvi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtntwonhtc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrymlsftm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlknitvje.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtvymwoleg.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gttjknewfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gthpmjhkyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsqrjeqr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtatccwduh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtjwdmpymh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtpulubakl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtxlvgtfma.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gteknlbwrf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtqzhljozp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtnllfexkf.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtkxvnqfha.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtrihbbuln.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtxyxoiqdh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtxzypgcab.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtorbclnga.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtveinpibm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtguoharun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtrghvpsna.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtizyaxdax.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtnkorapcp.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtunloomrn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gttikfceos.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtrxuglvku.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtuydfsnca.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtejwztrgg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtzzehazdk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtnhuvhbsh.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtwdsgqlhj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtigpjoeww.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtbswbmgto.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjovccea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtnzeyghrv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtxzxthcnj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gthbmzqbyy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtfksbljso.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbdhrfat.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtvcazcomh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtkpbiolyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gturxkijfv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtsakcvrjb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gttxoohmsk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtuaaiycgj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtntnfkpqz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtufvovtot.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtyhoklqls.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtwqtdscjl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gttaopoppj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtwimsluwr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknmdbuho.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtbohsxsgh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtksstfdfv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtgsmmsdgq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtqceufilp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtwcvriwow.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtgcwptnbn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtncuvcnfd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtsjswdzjp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtqptfcczy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtqgkykykg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtzcfplanu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkvbhhzb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtqeanhmhi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtdgssnaut.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncusxztt.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtzjfueerb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlqvsnhao.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtkznzkhpk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtckfloqpf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtakkdjvmg.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfpmffepo.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdflywjl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxodpzbi.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtyekykoqx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtglqflnjk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtuafgprbd.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtytvimsqe.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtlhaltsqo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtnwnzqnlr.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gthcueekvi.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqbmdcau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtskzkficx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtohkpracw.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtwwialehj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtweylfapm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtyzilbzsv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtenmewpog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtqnhcmouj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtvctqmruk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsyhikse.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtvsadtcok.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtsvcmqecn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqjwtddiv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gthvklmjad.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtyxfmslsc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtoqchgsym.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtksifewji.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtwgxzxqgz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtnheszmya.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtmyrwrmct.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gttjgrgvwm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtmnolteok.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtivrnvdhf.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtuwnmgidp.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkiuhdkys.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gtceqtwjoq.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtqkjhngmw.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtrcpzxbif.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtrplitlif.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtybfdekpd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtjgjbkerk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtbarmdgnk.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtjnywvizl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtqbhjcrjh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtozkhmwnh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjabdyexv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtbyvtkitz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gthwshlrre.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtclatfnuc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtytrindga.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtkceusnhf.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gttimlukzd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtlhkdgoxi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtrbquphco.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtsavujwvj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtsyvyxvmx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtxijcvnfc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtfswufibb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gtnxowrbqu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtrkstwvvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtujctpbvh.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxvthqrkd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtxokyhvpt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtftqridnh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtgyehkbjy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtwovwjjtx.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtpvvfunke.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gttxphjotd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtarontcjg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmghylfwb.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtbfrlaopd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnftbpunn.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtlbkukvij.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtytctevba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtoazklzdk.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtehegyoxn.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbsqlvdy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtvxxdgyau.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gttulggfsx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gthnqutenb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtktymdcdz.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtaszjfjht.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtostczowp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtrvskknwk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtabegnzlk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtabugfqtl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtvdmrimnu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtmrtxccwi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gtlmdsuota.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtvabjggkv.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtcemlqpxf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gttmnrwvqz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtcufdcvfx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtwwlfuagr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtgqmhfofz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtkswdaelr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gthnzuciat.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtobkbfltm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtlvireckm.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtekgxfzwz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtqbybnwej.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gthkdehsda.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtbpjqpihd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtkttrvkzf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtbqgzlqje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtilucowep.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtabefnkmx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gthmoqjbcv.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtspmvdpzz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtamhxonwb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtgcxxhmky.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtvnhkjdog.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtrctohccm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtkdkugeam.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtycdvhvxi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtwwzwjoea.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtypqpmumv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtlsbvmeij.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gtppzicrzb.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtiuqxwqgq.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtycfubodj.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtwvinkgcr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtyfsnyvmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtefeqmzkf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtgsyxgnnt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtnehtvjdf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtjbustcyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gtqdsipauw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtjdepivav.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtxvwvkgbu.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtuquodqot.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtgkvewigg.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtbcsfmwsz.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gthfhxylwe.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtgckyzwyq.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtejptjquz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtkyvbtero.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtckcbmnxs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtrolyojuq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsdjmyby.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtmnuwkezl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtcvsuympt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtmamhgluc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtekzgkaaf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmbasfmbg.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtkdskmrcy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtogjhlgnv.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gttyurvugm.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gthnfxmara.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gthyhhqfre.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtwxvxqtkb.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtbwewbhpe.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtiyuselcx.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtbrsgvbwv.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtdwnghqiu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvozurzjf.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtcsyttfei.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtnrsfyinb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtedvombqt.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtabueoxuk.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtcrcyigma.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtaqdamdzx.html


<!-- 参考信息 -->