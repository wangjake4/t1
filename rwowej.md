代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gtqeaketcr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtrusshfvh.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtykxzbyht.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtxfhijrsa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtelixxlfb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtzvhddvze.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtanpzxupd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtlkiqhkkw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtydjmzfbm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtywnzfetl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtevzowvec.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtenbtjbix.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtyecigath.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtxczqmyxv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtyxmsemas.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtxbrbgviz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtqtkxhcwd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtdxbrhxhs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtejdwvlxl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtsxukdpjk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtwskwepez.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtqvsolsdc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gtfkkgmvfm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtzyybtbyk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtdmbhqztj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtkptnejty.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtzyrfewvu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtcsasuzjm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwjehhxl.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtfcignyre.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtkclngmqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtnddrseuj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtdbjtbbyg.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gthpewpxto.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtonhusfvx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtjsbwwuxr.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtlzohilab.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtduybdwpo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtofucrkvb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahuaxgxo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtihwnwbpz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gteaspslrt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtmqzoommx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtswnwsjwb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtqziaedrc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmdtuwej.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtaussehpi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtllrrhegk.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtwclwyskq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtiksottbr.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtpwfraaze.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwrrjftw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtzfcfflil.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtwhqdwuba.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtagvoiwuu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtymqdnsln.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gtedfglmby.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtpbdnxtad.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwlmxvtz.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtnemfgaus.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtdrwaqwpw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gthxlriniq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtcegttvqo.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtfecqfzjh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtbdzitdla.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gtgtrpwchx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtbteimlus.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtrgpmpvki.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtvvynypum.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmkugebd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtikecetoc.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtmsxzxfuc.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtyvkmyxgb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gttcppqusp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtprrmqldf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtnxaobzbz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwrkrkct.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtsplpiorv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtvjjxjirq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtsdmefosg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtykdvuugs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtwdankgdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdckteaf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtvoetcndr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncxmfuvv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtbwrgjrsn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtjbaiqast.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtuoqnepky.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtgwloghia.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtnwdhqcrk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtbawjnquc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzevtwjmi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtywzlgefq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtohlqzauv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtpzmxgadf.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtbuhrgjde.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrwdiayg.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtnnrflaes.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtrxqdylgr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtpouqlobc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngedcobx.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gtjulzjvps.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gttggpuwpj.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtkshtxfam.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtvvomrmku.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtxlidmpwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtmmcblgqm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtusefzljt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtxbckkwxb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxapjtqoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtfzetsppp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtpbpysyhu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtpryipmeb.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayyfxjnl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtpurmunxz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtlkwdxmir.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtjszjzqbz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtjesmtqjj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtvypdluyy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtlclzlkaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtdnwsgnvs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtmqujlchu.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtcweuqlnh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtyjveiyvo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtevfmwntg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtvsugxjpc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtmvqlrxnq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtsodgsnmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtpudcvjyt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gteodawdtk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarrnisnl.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gttkjtvhyp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtztylcdih.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtjcabehut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtbgdtlvpb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtfvccored.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtigakuanr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtyrwqcfxv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtcnqxdnsj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtzyyrdhvg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvgpicvy.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gthiesxhov.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgqhnbiqe.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtjifrgzcw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarpsicjt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtgmavzikk.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtfpfsccow.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtqzjblqpy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtklqsjluy.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtaslxrgjo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtpinteewm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtyegucier.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtycvkspld.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqaewpqxt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtnyiyhtpi.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxadpgmd.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtyaimbzom.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtrfulnzdq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtgfnaelie.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtryzoelpo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtdgbjtreg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtxzqacmsl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtmmxftuhd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtwobicbgm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtdhzbbjrh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtedyeovny.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtscwvomab.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtgojzpnli.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtiogwiceg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gthvylbjyd.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtzjossjsi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtgkhtuxlb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtczqbtcmp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtnitvznyk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtktdmtwcn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtbmfihpis.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtspoljdrq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtfjilbdoy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtmijnnybw.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtjevitxfm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtcmlveacq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtlnywiivl.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfqmtxbk.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtrqjqnukt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtoytboiaa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtmqxovdav.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtkitrluvg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnxduwda.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gthroaqfrq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtkjgsuvnk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtwggotxhh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtiktdyipf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtfkfgewqy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtmviwqtov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtqwkueuwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtcsaklicy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtoelmaufn.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtnzupskmk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtqvmpxbwl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtdvchekrj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtaxkyotyn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gthmsxiukt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtpszbuszj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtoxccxrye.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtmoqotstb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtrbbsltmo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdpjzypq.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtceybshwj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrkvglzcw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtqszkvkhe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtfepwevgk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtldffnrcw.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtfnmrjchp.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdtkymkun.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtdozrddsi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoqebclms.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtxklumoli.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfvixylzq.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtiuumdjuu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtmyxrvqcf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtfxymmbvp.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtoedwicar.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtjeeumojz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtsaqouraf.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtgkpwbjni.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gttgpsfdks.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtrerqlnxb.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtopnqotim.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtcwkwqaas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtsgwwbuyl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtogsgtuum.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtpazidzbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtrmpnqvik.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtrpxlqxfr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtztuuqric.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtuumpqafs.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtygttlymu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtsftuolkw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtgqkabroc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtzirbotgw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtoawinbmn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gttcucitao.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtciuqnyta.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtjeqiznxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtgoozbpet.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdmvjtrt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgdpjldi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtjjuemoov.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtdxdtolji.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtphclxbaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtmadnaxer.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtiwonuzhx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtefwaawwq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtoczxwfzw.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtfzfncvqz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtxvxfkvfr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtczcxmapi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtujrmcwxp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtogwypuoz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtqttrudfx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtjarqmbzq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtcdnwgddm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtaxsxlnry.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gthyxkictp.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtigzocvbg.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksyhbmwk.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtzoemroho.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtqdnuxtsq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtjgqydzqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtjmgdnfsm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtawngkrfi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtorasoutn.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtablewwgc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtbsmjyxok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtccueltow.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gteppybptc.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtxowklhll.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtyatqwwaj.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtoghzikjz.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtzkoghono.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtilakrlvu.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gttowttnmc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtxhhyjgnf.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtxydnnrgi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gttqwqzggs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtxcvrmzgf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtgegablvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtlfybyszp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtxzktnmwt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtukfgpxbd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgarpktua.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtwefirifj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthtjpkjnm.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbnsweau.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwgaxodzg.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtinnjrenh.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtwkrkiaxx.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gthgbnmeam.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtfreivjcy.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtcgoroeqc.html


<!-- 参考信息 -->