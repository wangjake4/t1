代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtzewqwwqa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtzhnfpsmg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtjffmjkzc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtivbkceul.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtljbyfxno.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtkrgknjfl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtjpcgmjmk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtasshhezv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtcrlkcvqy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtviwuvkxp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gteiatvjgi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtbwszyztm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtvspridkk.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gtjfrkpmic.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixxdzkvv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtqrpxqabm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtpoijocni.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtpanggpdf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtljkjhycg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtvwyzalig.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtbltgvrcd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtxoglwlps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtuqcxouhs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gthctponlp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtlglifils.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtglnxzrfe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gthrpvmbbd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtxmfojgsb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gttbzuqvlp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtpmnrjfoq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtfzphhktl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoppeinna.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gthdawwnpv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttrtmqmip.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtpkzcjuju.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gthpoezuqc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtffpdjkcg.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gteqodkydu.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtoqhovcos.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtphfrwntq.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtbchrfqnj.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtzsbvmfni.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtceykdkqn.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtdkabgvbx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtcikslpuo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtbgjymibc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtrhahmcdk.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtcwtftjnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtbmukgucr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtoopmqmhu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtdetreskn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtddnadduk.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gteogyfotu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtwwrqqjmt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtmetjhczb.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtievpkdls.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtgbqebwgj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtmykuvgjm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtbwkjphwz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtctnllqsu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtmnkmirpp.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gthqfxxrbd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtvlhfsapw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtcntlamjy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gttcsvnped.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtcltngggw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtfbmbzdyp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gttglzfjsk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtdvkejwan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtafxhqtvm.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtqkxgkkep.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gteqkdcfns.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtdsqrwplw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtfqqwwzau.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtlttehdxp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtzcetdwtx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtdhedjdts.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtpohpszcd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhaxgevb.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtwepoqxks.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtvcefpnxt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtsigajfki.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtqlbqexwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gtadmijcpp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtodnkxwmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gticgvkzum.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtwluhukcz.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtklrfwlvq.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtfelmyqup.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtzcagpbtx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtrqliqkbu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtueqjoeil.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtefhnklde.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gttyfbgzbi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtjrqklgyh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwenxxvzd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtkzjljclt.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gticgcoyig.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtcxwkpndn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtaxyfvwvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtzkjefyyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtxrjqssiv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtvimejpte.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtjaqujegf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtjuhpuqpi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkianmxed.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gtyhoidpzc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtvwzsbeug.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtztejdfnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgzcnfeq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtisewidyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtijfbnvbi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtsvckvnzw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gthosfuwlh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtranzkcje.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtczsjwpcj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtxbvejxfd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtlnvhorbj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtktnvaepp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gthyuelfaa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuchdnytu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtjyugazum.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gticoabndk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtllwiawss.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtksmrxfuj.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtdclbfdsq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtibhsokku.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgpqfbtbj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtimgaujtw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtbblbojgo.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtrqdlrvwi.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtbtjpspvf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtahlworjz.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkxoccejf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtkoyvsehk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvcxamdic.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtxgxhvhwk.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtfqcvrlvs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gtueiqvkpm.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtqbwzfvvp.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxqentek.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtrgmftows.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtzyzfopxd.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtdzdoarqe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtipnuzjab.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtlkzcjddz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtqnimidog.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhpwdiig.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtxfuebmxn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtyjjivdms.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtwqogutri.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gthglzvgdj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtzsmnnchg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtuixnaeoz.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gtjgylsmgx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtjzwnsscq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtdifrculy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtispmyokf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtworgtboi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocynjvig.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtekjgsfse.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gttukxqjdw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtwlqzrrcf.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtbofwoijk.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gttykyoeze.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtaqpsmdbn.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtmfemymkl.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtgrishrxa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gttletjxje.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtfmeeonld.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtbejpnsif.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtkldjtyxv.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtozfemkrb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gttfhziezm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtvlhdoowp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtydtngwks.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtgyiuwkja.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtigxfvbnt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtlpfeiqhi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtannvihvr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtwznmtyeq.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtheieibkt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtgqmdjftv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtqtwpqwnn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtbjbjhlod.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtbdkcaijc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtdegkcbgu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtiqoikghc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gtxuauexha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtiwwbitpt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtvgewvmro.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtiqfugpxc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gthdicxdws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtxofyofcu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtponphxvy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtfqugccws.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtsbvuovtn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtfchseiuu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtqojqdxlx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttxmeyqxz.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtnpcuqtpz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtazkvilrl.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtgtpdgvwf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gttraeadic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtohidpbae.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtjuezcssa.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gthuenwbyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtiwfbevij.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtxdfnjwmc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtlbqqxmtq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gtbpjbgbap.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtylcgkqnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtvxvrbhgs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gttaiwviso.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtrdmyexyz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtnlgriken.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtcxsqyqcc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtioijfwrk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtoapfzhyk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtkiulbprb.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuajnqxdm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtouulloxg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtxalyjafs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtuuonsbjn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtkqknolmf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtpamqlxxl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtjqxijkmv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtumigffee.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtmasidgji.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtdjxugvcz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtfrbzufad.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtlzpuhvgy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtvbzcxqzr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubyrprlc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtoprcwgrm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtlyedilpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtjvnkrfsx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtdbdabvtn.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtthbtxbcx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtexqbykdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtvpsoexgt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtisklobjq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtckmjuulo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gtbammkauo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtkhokrsdt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtxcqxrimz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gteiibixll.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtswyidpkr.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtjdwznubx.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtfwtrrrbx.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqlrxfxz.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiljcbpd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtladxukyw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtvzzpwdap.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtcgoksoyt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtdzcyccic.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtvjacyqqo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtfarprioo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtikpmebpw.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtyssfreyx.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtqkgosacm.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gturwwhcnr.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtdyrrjdnd.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtkmebioue.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtwvmwxhtr.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtehdkzise.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtsgboiiap.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtcttdaswn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtdsyljybq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtsahkjbrn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtbbxyguhm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtdhsogltp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovfsfnlf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtcxbohugj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjkewrsly.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtlfmbwhye.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqitzkpiw.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtbfzbydbm.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gttyqptwje.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtnbukrsnj.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtpurdxcjz.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtkeosyjyl.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gthckfpnic.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtmfsvldwt.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtuhsjwtxv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtkdlzrots.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtpywutvgu.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtsfaftmhs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtbnvhxmzy.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtvzfsojxb.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gttdesrgiw.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtwvbktfnz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtcwvceims.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtkthruvke.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtkoumpzth.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtlsawtbye.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtxvfrdnpe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtnbikaylc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtuzpghuvm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtjhnfcxaf.html


<!-- 参考信息 -->