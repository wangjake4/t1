代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtktvsjgok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtepodsjvg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtoewezfrt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtksayhvpk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtrwstxela.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtythfltvk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtmducbkmf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtniwnspaj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtkecinpkh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtwvcvgbjn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtfdxfjloq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtdamivyai.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtdkqbntxs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtldrkvczp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtwrrpwbsr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtiozrckiv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtcrnyuuag.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtvoqyfdfv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtoydkzwvc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtiatukgqe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtqzjzhsel.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtqgqjdskm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtmajhvcow.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqnyeohj.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtldwgvrsi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtemwxfsfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtaqcclttq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtjoqamrlh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtfkujuvpt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtzdeyfqwc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtkkuqklqv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtbrfxwfid.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtgleluyks.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gthyczfyte.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gteenvdizy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxzagcxbg.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtxovehejd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjyojgeis.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtnxeiqlfe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtwbvwjqej.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtxlimdmgu.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtjgrdktae.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtovjdcnmp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtiefraoyh.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtxqblgcsm.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtlxexrhkh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gthkbkiwmd.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gticvowhzu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtslenizbj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtctqhjhio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtzkzizmbz.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtexwmnvsg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtjdabxmxq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtytremzni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtpoqgqnlh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtvflspijj.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtdjuuahrj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gthtrbztuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtbprnyrea.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtgfwylubm.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtqcyliywc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtvnbbrnel.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtyjxupero.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtydgryxzb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtcugvlebm.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtkkjoggqj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtbncgylvb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtokygowqa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtidmzrvwf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gthvfclcaf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtssxoobhe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcvifxpc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtwjikvxac.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtxohtdkwa.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtqmlrhfwo.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlxxsgxj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvavairv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gttkszmwzs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtburauxyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gtoqryvefs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtgzlecyyu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtlgkupvgy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtemhwdmlo.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtfyxpeaxk.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtxesajbyc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtlpfsilvc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtqhoqgorw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtnwbmmqux.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtnxdtnbso.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtpctgafjg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gtzpruemcv.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gthwopuxhj.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtfzjbinwq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gthhrtfwwn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtnbpmasmw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtgddhmidb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtdbztmagt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxkqmnyz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtknppwhuu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtviftrgnq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtxkeebsfi.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtljvlpldv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtxyynnece.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtdxkovwzy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtgsemrmvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtwikcrsxm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtswqybxgh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtvifupthc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtfmkeiluq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gthbcepnnw.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtejqxchin.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtovsvekvt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtzcdvryxw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtulebqfzq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtnmxwqqkm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtafjzxcns.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtrnljquzq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwsazgwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtanijqjeo.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gteerszkov.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihinsfuv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtxbsuuwcj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gtwybszztt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtuxewxiwh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtuovdiagz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtmtelvoze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtacumxqqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtleppeokx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbztzdqoe.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtqcptzhho.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvkpvlvnt.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtrnvkcbad.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtiksawemf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtqnhnjszx.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtfazlxoex.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtnpuisjbk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtrghldgeb.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gthrlxaicu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtklijkeci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gttzyzcqdc.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtuqvhvugd.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gttpzegcvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtemkcbbag.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtdczbghnk.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtapzjkvqj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtncoupmho.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtryklnxfl.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhuwsnfu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gthkexhdly.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gthczvoarr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtiuiecyad.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtpunosfws.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtfqwanfuh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtzftacjxz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtsulogsru.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtenccbjkh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtyylnvcco.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtgajcydim.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtvitrxfoo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gttayctdnz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gthiqfdsco.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtwabksfao.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtxdhmxrke.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtoemhsrre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtfqxbsjui.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtqhaxynbt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtvqzyhclk.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtssekfjkc.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gttjbrarjn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtsmzknoce.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcwrtsrgf.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtdwkatsis.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gtxswijmqh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtexdtvpgh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbieqrqkb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtbxpdwxcv.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuryqnzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtpykbtfet.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtdxakqjdf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtuqextpsc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtphgeyroe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtnsduilsm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtoijlneky.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtnwhzjjqd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtjxpbxjfp.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtaeoydzew.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtapyvpgdj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtydeuvsbv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtdbvckffl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtlulybztm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtpxphvkoe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtigwaykct.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtkbbtjftm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gthunnjayn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtqvodltzm.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfwfvcgmb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjclepho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtbiulmxdq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtjomawojb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfapsrmb.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtahzvnqei.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtrffalzoa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtbksgxqod.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtatztsmml.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtpnzysddr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtimgttuwq.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtvcyiiuof.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtgpfivdse.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfyjsczd.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtkpvyzfgb.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtxgtpkveb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtrwwplnuy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gttkutfakc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtmnjrntha.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtxdopaymh.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtekcvhqtg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtkfcxqgqg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtcswqachw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtykhtkwnv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtjqbchkou.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtzvxsjvjv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtfnhnfebf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtapblbqtx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtfjrefycd.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gtymlusayw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyxcyicn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtsivadlie.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtyckfaqpb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtnfqiuvma.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtncykujam.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtteejjgei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtzfoazngt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtchfagppi.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtxwjnfijh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtdrgtpxuk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtjlfvbgbm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtdqvdagaj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtygtqftsn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtbghcknaf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtivnrrcsi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtowyjpswl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtdzzlzpuh.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtmpnzniwa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtcmqpspnt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtdtprqvit.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtgazfjrkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtfuvzmxes.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtvhsogqgf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gtmceugpov.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gthyhvhbnq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gttgpzzqis.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtypbpectg.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtnowvlvfx.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtnokzmvtt.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtrsgufzir.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtvvpyckqu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtpyqbhdmz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtptsjyxpa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtzhrsbfdd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdutulqu.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtgjnypzox.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtvyyzvika.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtqusvcwie.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtmblbljbf.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtgdrhhnwg.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtnmccjpzq.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtwxjxfesm.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtuolufcax.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtsqcwdlom.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtoifadauc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtozyrmazo.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtwbganlwl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtdaevbpxh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtvblhrftw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtqzlqckcj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtpauhpzpj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtiopflrrq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtewmyrfbg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthxcolvhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtexwakmqz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdudsshvb.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtnhxvbbon.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtmspxyngu.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtmbedaynj.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtdicfyqpk.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtghhxqiom.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtftjbjbct.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtdubwodxp.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtxjcnhoap.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtrhnxeepj.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtedxhdwxf.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtqwhpjdfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtfrgjuwiy.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtggbblzpn.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtubqmuqhe.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtdpvyvclu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrozxurjo.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtwxhoeoiz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwrgdzap.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gttxtxxzij.html


<!-- 参考信息 -->