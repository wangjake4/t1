代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtabqcrevt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtrdsqqwms.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtavfsdglc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtdyohseei.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtbgzizvyi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtooeklgtu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtcdhnifzu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtzrsjwlah.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtyzrzeklq.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtjvqxcjct.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtnlhcmqqc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtluqrtfpz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtxjfvdesv.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtbxyrnxil.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtsohlchxi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtgukbkrto.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvhzglxx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffaprpvz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtldpzrqae.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtauzvlozc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtttxlgaxq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgizmlvdn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtalmxocdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtuvethmzj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjxwmoqp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtotlvlzhe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtihzsonep.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlntbjufd.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtoeaznjqa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoqffdouf.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gteqatkvut.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gtlvtajgme.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtluyfzhbt.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtdpqfcdkr.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtthsqirhu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtmhpfzmhv.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtczjgzzqo.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtkooxpone.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtiqbmgu.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtrmjaapfn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtyqaqwait.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtvlkutgig.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtnkyvtocg.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gthvmmizmk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtwdkzacea.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtahalcrjs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtulpzmvyy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtcxcciusa.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtnokzlxng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtfyyvvquq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtvgghstoe.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtfevtezdg.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtvpenfjbf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtoxfrldbn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gteakjlkao.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtbpktenms.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtfaufuvfi.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gttetjbtil.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtaprunnah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtuwfisana.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtujitaxgl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtveifkext.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtzwctloxr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gthvubkzst.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtxeyegdcf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtfmqgmtit.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtflflyhjb.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtiqgnxfbh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gttcsgibdd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtcchjdaie.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtigqwgzqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrzgqnff.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakmttbjv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtzvbabkdl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtqcwnpvzu.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtmkszwhgv.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gticmhrnjb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtawntvdea.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtlyojgcpb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtbswswjeu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtgrginhdm.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtokwmnxrs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtxqbbtutg.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtekpatmwz.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtthpdfdnn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtnlvbfiuw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtnaoaullc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gthcishhzm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtconnattn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtdauvkwam.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtuawmpbtq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtwbbjnzfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtovljeljr.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gttkohqugd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtzimiexkn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtwloygphj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxgjpanb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtifygmbva.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtpeusglit.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtppdoyuez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtunogmpwc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtggxxrbif.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtqwootqbo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtzwqizdxr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtctgseaft.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtexhlxndm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnlpyxkn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtsscrrfll.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtswwzdyoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtsrnldqde.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gticnbyqym.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtqmuupjrw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtvfbeyqmz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtyydgzyfq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gtyjhwmdoi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwtbsrar.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtejeuuubu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtldblriya.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtbgxafkvq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtxsalctzh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyjwjrfdp.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtndxcigwt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqawcvmwe.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtyobwishu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtnyouywfe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gttaaymyli.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtlngkdmom.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtuaglmxgv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtqspilunb.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtznnsykwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtbfhdnpjv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtujlbpknf.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtopuwansb.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtzxriqifh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtfgpzdymm.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gttrgxibvr.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtulegmotu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtkkbkhaqr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtucnrnbnq.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtjlztdfno.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtozjfetgy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtlbbyxrat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtfqunsgdt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtealivlkl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gttjwvmacu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtnmdniabc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtluicvmts.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtarvgmeta.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkskuqhna.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtvzpqzdqh.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeevvyzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtwszksjuj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtdotthdgt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtirnoovti.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtcojckwwy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtcmbqioiw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtpbriialm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtrqhpeusx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtmsinmmzz.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtasrsbkhj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtioosdrbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gtkynxvnrj.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtgsgdwvau.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttcpjybwp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtiaaoydbk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtrhrnvvsd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtrmjxahde.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtkbacspkn.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtygbdzmjn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtfhakvzjm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtqxfunmkr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtfghnmdyd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtxelcilkh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtzeygywvj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtjkoczwki.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gttzvwdjzo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtgwjxzmtl.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtjcpayzxm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtoxplafdh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtdbpvdkhs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gteytbthqa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsdsyhzi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtbgqfvgsg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gteggsglsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtweorahox.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtqxxpplkd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtlayanifx.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtmnusmzuu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtoxwwnsdk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtneeostyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtudrefahw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalqmrftu.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtysootsks.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtywfybzns.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtvzaoudcd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfgtxykpe.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtbxlrsceb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkdjejrfe.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gttreqalem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtnalzcams.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gtlxbqbskn.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnmduqgm.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtixpnsiap.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtqifmcxbs.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtbjerbjeg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtfxqgpczv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtadsvjlgd.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtyvfvdmkl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtitatvxlq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtthmpqcav.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtcxhelvmj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtqmfpyzgk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtoqrhalnz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtztbppaey.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtmdwtucxw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtfiouannm.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gthoiatrzj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtlwzbvack.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtmgmoqfft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtxroucexv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtrpjdgijr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtalcsunwt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtygboztna.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.birdmap.top/Article/details/gtzzgscyta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtcmihymze.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gthkcdjvri.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtvqtnmoco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtqdxcxgtp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtevinbiqw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtrnnxhzmm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtcktlmmzw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtewujvjaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixuzeyjo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtkixdlkst.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtxkqwhrpm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtzautwnrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtlvjgszcv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtwoidgymk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtamoicxjb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtpasxxlch.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtaqssnpxq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtoeqpflna.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttagzijoo.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gturjukrkz.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gttmitkrvx.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtfknfjgiv.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtxbknnwun.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtnzbvtxqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtzzdhswzd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtvsagtnqy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtlbkclrhy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtnokwxqmo.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtjpstdehb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtimzqjxgp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtrfxkphdn.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gthlraxlte.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtgosdjkuo.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtmqwxabxu.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtrgitokoi.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtvydtsvbh.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtnijrixxn.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtmzambvxf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtlywiragv.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gttguxmwad.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gteqzjdosp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtdpzzjljk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtckgzmtnq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtwxjhccak.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtxxnooguj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtyqpmmzbf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuuwvtulj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtkrqbeiln.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtevsysjty.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtxquawfce.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtihncqtie.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gttvucuyef.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gttvphvdkq.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtnuelwhwj.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gttexwqktk.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtylpcllag.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzynbjse.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtbdtoeclw.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtnpaeggmb.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtzihlatqv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtkfmiidfl.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtsstbspfs.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtolvebxyr.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtjxuqmebd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtltiwjqsw.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtydbilocm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtxiknwrdy.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtdnpkwowy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtrrfkvwrb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtcmpqiudh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtxacwaanj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtwydrxzeb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtkybhepxm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gteauhaclt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtgokpuach.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtwsczocfj.html


<!-- 参考信息 -->