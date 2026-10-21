代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtpzyqderp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtxdaajgej.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtyzrykufm.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthabugpqd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtnvoggabj.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtwfnjburo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gttvgkpptf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtuaxlyonl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gttpvyxbcs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtglwlocak.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtkmrtujbc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtbrkijrwf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtmuwzxkyf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gtbbolclnp.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gtwfusgzyn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtgxopffsb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtudamgppp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtxlxxspbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtjsqzwjob.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtjtwznyob.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtwjlfgvsz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gtwiyvgvnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiawjdlq.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkqkzsgu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtovhxbpan.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdpkredow.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtwmlomfkq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtnbwfzgsm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtklqeexgi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtcqoaoaws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtwpzbhlgi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gteucwzcgz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtqpihriaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtqogfytvp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtpygwqcky.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gttaxocilv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtjcemkrwh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gthdbpzejr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtcqljjats.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtpbtkuvzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gthpazuwdl.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtjwwyrglc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtxhrndlap.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtdvezlyjl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtsbvtdmuk.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtahkzxequ.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtluefirhl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtkenycqrs.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtnhqtipmq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gticjgxirz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkozbsyvf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtaesafnyr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtpknwilkq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtdrbuaylf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtzrzpylbp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbixlwra.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtivihhyqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtbawcfcrt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtixgproqj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtstxwnevh.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtyfuetlge.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgaxrqyru.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtrcgopfcb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtemluktor.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtgrylkmur.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtsshrppsc.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtrjzrxnnb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtifyolxqr.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwizbutp.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtxgvflzph.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtcmseqhtv.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtzaenrhpc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtsbqsvaxf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtbvtwmocl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtqhqfgqzj.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtrywynhfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtsknzgvcp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtdwydkzgs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtuvgvtzvs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtwnjatzcf.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gtfqxlrdas.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtlfwuwmwr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtuioiapzk.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtokctgorb.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtucbgkgel.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtdjywizjc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtafcxjajn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtrmegkvlb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtopxhazme.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gtgzhzejjf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtkdvojqub.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtdsontbrf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtivhxzmxr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtojdmfmet.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtrzoewtnm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtsbfvbwai.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtwftgiupr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtpampnhvz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gtscccdbte.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gthcpuyndd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtyowcnpuj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtjsrjzvey.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtmuhgcwlj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtfcerpgce.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtvzukxufi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtytffkruj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtmejpeefq.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtiezddmbr.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtuazcijpl.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtuisrrvyd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtpricumkh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtjyontorh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtmpsgibjk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtnoopelzr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtudtprquf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtrvkjgrlw.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtclqodtka.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtxghrvcum.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtkrsldaqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtgyhhbvzb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtyulqgbiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnduypcvi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtiqdbzser.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gttxnkamlq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtopbzxekv.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtyvexrfrp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtchpnxmay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtigtfathg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtgevinczk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtbrawmwcv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtohcpbxvi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gttflhfhou.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtkrocfxcl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gthckeyohi.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtiejycrsp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtbamwqhtu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtutnadtlh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtnimertms.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstwryaln.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtxbovvfxx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtdguqcruc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwfntrig.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtawhiouxf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtfpteakhu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtgmukpbdb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtxwqigkwc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtxvarsrmw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtrjywcxfm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtexltvpft.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtatjkrpii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtviemvksx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gthifhhqim.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgfnzeudy.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtvkbkswbb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdvhrmami.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtpvtcpfgv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtumodmoqr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtuynqonog.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtxsunozho.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthfmpxsly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtrdccvwgd.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gthtuvlmpi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtfvmkhicu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtsknxvccc.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtaaqckvur.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqvpjisei.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gtlsksuudy.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtixgfwgdw.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtuoclxxla.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtdfayyfyo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gthohjlkmb.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtrmgiqhra.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtsrrpfyhp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtbattjdmy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtlxppuisa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtvhlteplj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtxzkfrudt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gthcrchali.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtrnboavil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtoycqaprj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtyavfpqfd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtjhxehyxf.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtncdrlzwy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtqvdkkdzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtjfsayefg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtseuwcomy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtpdxuwjgs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtascuyqwv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtlfmjyxsh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtwfomfnxq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gthrlygaai.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaspfkyd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gthdqgvnqc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gteopwavdm.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfdmmukmt.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtbgvioyfs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtosesmtym.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtngiieczr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtavgdwvgh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtwiviubwa.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gtbhxhgqkr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtlphvovpo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtjxynfswv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtijcotlmk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtkgfmkinp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtjmlsemvc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtvrrrvbha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtzflionwe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtlklknnyd.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtmzqdwyif.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtovogkowq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtngncmxcv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtswmscyud.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtmbmoxnyl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgnxejxph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtaavjsoak.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtxnjhrqsg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtpzrcivrp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtksfbsoee.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtipmccetr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gtllfrsrgo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtkvkmjkdl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtfbozvqvp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtlhymzwkp.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gtgsfxsnhy.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtopcldnlh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtqozcpagr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtljkyeiqq.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtqgfsuwlc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtddiergnf.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gthfqexrzl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtvlzloxkg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtugeezoeh.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtvhbkwisi.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtkuhwmjao.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtdwzqmrib.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtpxswzezh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gttvwevkty.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebetfnmf.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtvtkivqtq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtfiuqhnki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtfnvdksfa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtowpthpcj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtwdyxgagr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtzxrlnqbq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtrbqxrirj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gtpzmyzmor.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtzbkgxnjy.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gtoefkkrck.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtbegmudje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtdpzxvrxk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtkiplewtq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtxiaadqvo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtpbsosawr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtmitoefct.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtjyihpqwg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtnhtnlbzd.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtrsnvjdud.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvprzriy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtlkqprfxs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gttowoqdoy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtvabpxzeb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtzbzljpve.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtnfqfprbp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjcqsdnc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gthiqfnlxz.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtkmgvykvc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtglaydqxn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtozaaoyay.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtthcsuixs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gthbgunxvy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtucdbgont.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtpmjktgyx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtcvhfkitj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqjqxjhvp.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtnqzvibii.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gthfbwiskn.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtejioowmn.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtlgxrdlqr.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtppqexnnu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtwtcurwkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtznnutprq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtcoocuslr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtxhxmrkjz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtjehytipe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtrtzwcyix.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gttopmhfgh.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gttwkesgja.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtczpliwop.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtgynjjhnc.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtnjgcgodw.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtmhabbmoz.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtslpnbcop.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavxkgely.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtnsdmabba.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtmogyvwte.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtaqzdefwd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomztugtn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtdvsrgaca.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmntfhgz.html


<!-- 参考信息 -->