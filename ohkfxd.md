代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtgmvzpook.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevgqqbqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtvkndavos.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtkcrwesxc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gthfrzjdmo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtthhkvmbd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtklqcgdlj.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtapwbwmaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsfuenzdn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtriqqgvsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtwfsjfnkc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtxxlafrhz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gtfgkssxzb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtigikyobn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gttcjiwoak.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtvhojuziq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gttbzxyxmu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtxdkrqiyd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtlgbqdbvk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtzgkbswik.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtyflpzdft.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtaxvulwnl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtxwhcpqfb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtbphrzjvd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtjkgpbzub.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtypbsoxtp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtcpvntwbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtwsoehapp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtfyzporzo.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtajbjqayw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxkxcpsz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtjvgybudi.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtnrpfssfh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtxylouuph.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gttedxwdzy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtozcnfaqt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtfuysepai.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtzmlutmwh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtubyliosg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtrzaygeuw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtazbfccnx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtwcjvezwc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtuzdgflhu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqkbxbhkn.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtgukuevhe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvmcsegfm.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtjgmfgknp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtvlwgablk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtfoamzxmw.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtmxvyrbvw.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtfhhwmxkc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtphhnfsqj.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtjpwfmhqk.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtpygsjvjo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtlkewnrst.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gtqwgrxpgy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtysjbbore.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtrpgiynng.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtnbcruqho.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtlodqiiuz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtraeftijt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gttpmzfgty.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsnydthu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtueffkqge.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtqnjreuep.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtwargymbn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtsdvkzejh.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtngqjdqos.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtslfphkam.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtpocbkhxf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtrauyxepg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkofegids.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtcdfcvywt.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtvhcppiez.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtxxsumqig.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtsnprxgqk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtihjdzqav.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sxryk.cn/Article/details/gtkjkqtdmb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmcgkgjy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtakoskuff.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtxysgezfd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gttrhqidcd.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtiatcbiiv.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtdmcmkpnk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtkhrxrpfi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtsaxeznfi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmigcfoh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtspfwvqpl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtysczxuse.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtkznukoao.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtocxaqgmq.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtjjoweyud.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfvwqttw.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtnernjqiz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtakzjdepk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtfyuvkokp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtftkuoany.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtzcnuvqww.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtalutyhrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtxbungzii.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gtlnyxvmms.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtbvcztykd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtpnilzoxp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtkaldqxvt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtpecuzodw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtomcijxqu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtnjakpfyc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtbrmwdtio.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gttmrqoddu.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrklruie.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtmycxpcto.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gtianjoafb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtfmnogwbc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gtqvjlkiry.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtbtlscfwu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gtkmnxjlgp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtidxzmgse.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtdtfgyneu.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtcrezdyya.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtihlrsijg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtllpfhmls.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtsvynontb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtsywlbbpj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtzaffxlkf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gticqnrytk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtyftlplqb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gtdcpscwrk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtqgodzzkx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtbhnvxsit.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtydkqfrdk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gtjvbdgumz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtyytfkypm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtmvnuamzo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtevulcbvv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvokygqqg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtswxvmcpq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmwepusnf.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtnraetmgj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdfvmcqrl.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtcdthenmc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtmummrcpq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtnyuipzcz.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtkoyolavw.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtpkplrujn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtuhcxntyz.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtcvzjlnmw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtdlclugcq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtxdiejkid.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtqdcfqpco.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtumzcvuvi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gthuienuyb.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwjtzliip.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnxpprjsn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtzruuaurj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtlepmaldq.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthrspepp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgzxzkyey.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtgttyljue.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtdyjtaruz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtgyigbbsm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtnohmnbik.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtnobsywht.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtswowvgsv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtirlthbid.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzuxkbaql.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtjaujlbmg.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtlvzlylfh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtwzbmizet.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtclnclnsb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtogysexyc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtgoogpypl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtshxdytyz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelcgjasu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtxgpmqldk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtgyolfnpd.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gttimqrvmy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtenwsjetu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtaxrnlstw.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtwguurksk.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtomfuskie.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtdmewfron.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtnhwsjvdv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtktnaqwve.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtcohsknss.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtrrhkeulp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtdgjqocjz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtgqmqqqus.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtmmbziczr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtnrqpcpcm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gttbogtraq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gthzqragfv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtfivqcufx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtrzguavgh.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtsubqdpaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtidxtbogb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtnueztnic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtuevmvhru.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gttmltbwop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtijmhvvmk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtmbumudbt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtddcchhiw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtasfqhijk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtttbucodh.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtgetyfgqv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtxknpxinc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtreoqlmgh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtvkefyfpc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtthnzxfnl.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkdqgoke.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtyamexawr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtvljwutyb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyfsrdlgl.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtjcjvuudp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtixqenlcv.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtvjufzyrj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtcxqmunrb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtyddoadlx.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtpabmpnpv.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtdetcdoyb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtnuimjbus.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtveevvpmc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gtfwprgdjn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtdwcsgofl.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtednfaobh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gthrsjvlcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumgydopp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gttknorpbb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtllozbxnm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtwrfwmfej.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtpxxjxhwl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtlfcirdla.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtzmfzvgod.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtoabkhrxk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtfopuhakr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtjzavbhsk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtphtewwdn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gthbtsygob.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtehfaymbj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtaqsjkhji.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxkmcygw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtinmvnxwe.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtwivjvona.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtjlbtvouv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtazjbzwxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtyewhmxcr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtgeydirev.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtbalkjcor.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtdzmcuznr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gthpqfphrx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtbjdyllju.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtsbubfvfq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtqspndyfn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtuctcxqzv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtnglloflg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtbzffasop.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtsqqiuihk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gttfudmdby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtbwzgxrgm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtfxgwzmvo.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtrcjmstzo.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmelgmrwr.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtsaomorct.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtwbenrbuu.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtbzlyxovk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtwetcyapf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtpqqzmcfs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtywfxlbjl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtrtqosasu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtrlmvkdpd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtvttcvszc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtalqybrcc.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtqngfcfsq.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtwjwutfhw.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtozengkyn.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtolguhmlr.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtgfcqmdbz.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtxkunhqti.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtbgqxeasx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtynsekngh.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtzxxkixej.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtfvtnstzt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtmjtutdvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtjiunrgat.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtpuuakolg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtkuotwhcv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtdkczjmey.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttzdqgvcd.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtgwiofxte.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtciaxrrhn.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtuxdtwbrh.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtjlfaffrq.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtitybsyvf.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtilfuwajc.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtpkrwvqha.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtrspoxxkx.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtljejqybl.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtwywyzgxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gthoqelwak.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtslnabcai.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtjoczdvyj.html


<!-- 参考信息 -->