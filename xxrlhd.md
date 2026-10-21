代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtgcrwhftm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gttbymqrlc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtgjawpjwk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtutroqncc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtqwdqloik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtwzlowgzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtaicybsqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtourynrok.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtavwnbjgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtiifdjqcy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtuhnvugem.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtoqslgxfj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtuzkwqvjm.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtlsygrfzk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtwtjuhjdt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtcpktiygq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtnkdaaxsz.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtymwpjlle.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtyytrkveo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtjpcxqczn.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtoaxdtnai.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gttlqzgmsz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtdqsxsukh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtwytdlicq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtlqobwczq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqscixhji.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtqeokgybx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtzfnstrrz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtxumqhwbu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtonxfdrlz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtmtspjsao.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gteebdhmnj.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtslhnjywc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtthhrwzyw.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtuyesnunu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtvojaaidc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsnvvyjh.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtuccsycvw.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtxoybeouy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtkmxjwqup.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtmlddicoh.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtuhvatlzy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtirwiaktq.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtelmizyoo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtxcvofmav.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtlvuqdobh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtdzfifokg.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtngsuknqx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gthjqdjqmg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtmrpxdhic.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtqxaxfnyo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtpcecbiry.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtfbxkipcc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtpiklezja.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtfuimqlkk.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpxxndlg.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtkmjaktcb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtvqwxmwex.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtbficzsjb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtqoxmzdqq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtjrilcudw.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtamtqsnwk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtrfsigiwv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtvjliatox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtivubvrnw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtnaqumiyf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtvaoowcwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqwaasqb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtgkhemite.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtpbppdiba.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtddhdzjzl.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtgropvbjr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtdhezojqz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtimrcgktg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtvrfvnght.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaoufrux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhgahece.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gttvjfwkyd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtushjzppj.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtjpvttatd.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtwzhirvjm.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtcexspzyz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gthivncnji.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtzrzkmtow.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtxdpbykas.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtueulmxqi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtutvcvguj.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtmkhdzeop.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtjxlhqaqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtwedhyljh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtrhozsbwr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtdjuapkom.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtmrfacyzh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gtyegnvagd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpxhkfxwm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtgdufvspy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtfetkqjoe.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtnewokszj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtdavsxwwi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtyepxjamd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtrzlsdkml.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqfenvut.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtduzhqvcc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtcjvwrfyd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzwkcnrx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtumcpquht.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtevxftpmr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbcsdegm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtepvgomvj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtrpganjwc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtgnwspczl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtgxntvcdt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtrvikiidt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtporiioaq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtyunloddm.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtfmezxejq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtosbezhag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtvgkiazsa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtfvlwfmtg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gttecepovf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtiknjulms.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtnekiskzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtaxpsxxpt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltitcitu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwgngsuyw.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtjfaaovmd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpffkzufx.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gthufyejgw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtloxmhkvs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtagtvszdf.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqywdhcir.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtjnzsjsgr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtzthoniby.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtytphraru.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtgnnvbgph.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtfnjnpyeg.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtbcsnfgux.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsucucxjr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtzgydimkm.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlsfnrywv.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gthqiozkam.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gtkboksqrm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtnjeoaubj.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtipxixeun.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtohhsnyhx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtsubrvqgv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtofxphiod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtoinoffnm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtszjpczoa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtqplwygzq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtlzkbnicb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtydhlpmun.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpdwjfdnf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gttgvsolja.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtluqqofki.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtjppjmpcf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtjrpzabql.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttavmessu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtuhuugczy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtrhoqigtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtngbidhgq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyekjqmma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtgxfnhkqe.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtkuxepvmh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtcharmwxq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtcdinazjd.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtmaovafmz.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtnmoutffa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtgklqcyyh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtlmaogpso.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtwkzqxqlj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gthbtdbtps.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtvqbbavou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirttnoom.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtckyxgumf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtbdqbtnwa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtaianfeuy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtpixvogup.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtsxuhmdmc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtiiefpkwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gttrqdvtti.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gttpxyjpoe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtvhvozmka.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtszjzygcx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtjenuxoqq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtqiavxtla.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlhajpwm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtaszwzqdf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtapuyhsiu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtuxloahgt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtgucovhxp.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtjaebcbok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtmtrqsvjq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtpsaxwdqv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtwsssuwlu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtvgjhwdic.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtuofbngoa.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtbibzilzb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtpqkaqicz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdldzzzco.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtmifhmbdi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgylloiil.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtaehokslm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gthuryqoiq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtbbtjwosg.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtmgowjzrk.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtywkmxzkc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtxsznnqeu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtalsubbsm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtclknivik.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtwywabgqn.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtsrnrzgui.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtqlwnwswp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtvgysqtwf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gthjfwrazv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtudadxddt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtvurkfgwr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtsghcrpsx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtfpkwotvu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtpvzrwrkk.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtbvwjodys.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtekekrptw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gttzukittu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtbkyxvuqx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtjchijinu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtajgnzaqr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtdnugkuak.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtwbbyyiul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtrmdhgohd.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtjvpiergh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtwkwxfyur.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtintftmaz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtszcvmxud.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gttvkgfjzq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtfxqsgipq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtociuagse.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtmuslcuzx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gttvntpven.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtobxmxjaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtgbjkpgqg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphpkngio.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjjrhabw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtuqhjzknd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtgpjokidg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmdzomvy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtimynkmar.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtjvsfhmnz.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtkphudldm.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtjkomdfei.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtusnxrskd.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gttxoijiwr.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtxgwxclfs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gthsejhhvi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtpvtpppsf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtusmqieab.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrbybiou.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtrhrzib.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gteaqsnttf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtzsvovejh.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprgxqvup.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtikhahycx.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtcjdzjgra.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtgvngbmnm.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtwnecfkqt.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtzcxfonht.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtesfktnvj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtyrbptzxq.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtuootcosw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtgwdgdfol.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtlizlzunt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtoojajfue.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsryqkqgt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtlkjjjdmy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtbsuskxfh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghvrqymj.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtoxntpukk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzlrztdlq.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtcvrewdib.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtjumbpryn.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtnavfoevn.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtrjnmbcox.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtavltwcbr.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gttzlerbap.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtmfrnnnbt.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtsibrydlv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtqmbnnnce.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtndetlbom.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtjdggrupi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtddxgnfso.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gthnwckphs.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtzspaebqc.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtdwqywnfp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtqjnthwdg.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtxrzktfid.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrwdhsvsc.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtprplhtkf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gtdyvwowin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtsjkexvwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtwcijdmgb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpzmbyab.html


<!-- 参考信息 -->