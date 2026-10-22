代发 wailian999

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2nghulxui.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2cliljqye.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2hqsfoazj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2wpikxiyr.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gt2yeqoucxz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2dxbyibct.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2prokeicc.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyapshou.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcwwehoe.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epbfoytm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2fioouznp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2zrkaxgln.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2xdlfcstk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gt2zoxudbjq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekvidkow.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gt2dsqpuqou.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2ijkuuxne.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gt2hqpcyoez.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2zodsdadt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2vzzkjtjy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2vmovplwf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xoncjcms.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxzaywwh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2kthejutk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2auauxnyi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxgpfsti.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2iqfuwhwa.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2thpgnutx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gt2npaagknh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gt2wswhnllb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2fallnasw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2oieroycm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2esfntwol.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2iceawsrf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euvfscdf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjtzrdof.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gt2yhrjfdhr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2iuaqjujt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gt2fohgyaic.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2wabzaiky.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2mxdoxtaq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2hgfhlawy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwhdcihp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggqdfxgy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2fpjyzlzc.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gt2xdrqqtdq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eltfrtie.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2kpatghqa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txusbpnq.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2eacimffr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2rnxzayjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaelutpc.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gt2zisizpxi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wygysebd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2qokeenyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.c1oappe.top/Article/details/gt2qsrkmmxx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2zrskbdym.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2oahnqbwa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2jvnqrape.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2gqphqbsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2hzxvjbhz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2tnomnzoo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2hzocqbws.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2awuiwwwc.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2xhtzjogt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gubcjukc.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2nncqxwah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gt2vygkfeum.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2eqgvwwbc.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2tkluawao.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2soncdxps.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2xlzdgyxb.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aamvmoud.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpikoscv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2drjqzrfw.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2lhqveumw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2ehwsdgwi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2afkzpqvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gt2dlomxiuo.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2vtgywuwl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2vvqkapsd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gt2scaowwyd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piuovooc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2baxnjhnf.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2jefxorky.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gt2xsjeovvy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gt2snovxnli.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2qobcvqqb.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2tjymcjvv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xaqoiezk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2uxtzahkm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwbxvemu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2yyanfdrv.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2xfuzuorv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2owibikjn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2wdjdlvqg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnmoxvqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2btpflnhy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2hvjbcomh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2brbwyprn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2lvxwmajz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2wdcekwlq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gt2evtpeobs.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2quvomzxd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcsyklsu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2pvkxelof.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2nwlfmkco.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2bxsnenjx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzswsagl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2wgozrfqu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2bjmuszsj.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gt2jieuiwtq.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zszprcnr.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2qsnmctmc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2envvmhhs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2vyvkkupr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gt2ccbtricj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2knthircl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gt2hmnexxbv.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2tjbxfixo.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezqhpfhg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2llpoaznt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2saqmbieb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2tuvoviag.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2rfmfvjmp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gt2ksrzlgyi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2uudrcono.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoclpbgq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2uddaewtr.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2ezxlfigb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gt2ebfkovok.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2lktxtjam.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2avxminrl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2strtnryt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2aycjrynp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gt2hnnqkgfa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2oodgcify.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2dittaypm.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2ofsywvzx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2csudwakb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2uhnqfnpl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2rvqzvsss.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2siulhelb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2tblpguon.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2itkfuiti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2ahaklydx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucfdbrhq.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gt2offefrnd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idkrskpt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2cjdlbclr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkqdxjjs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2swgymjmf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wxmccswj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gt2dfsqbxec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gt2mvfccqkc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2ggxzsszi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2urrwixkb.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gt2xfdgrutf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2lvesnrbi.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufiflcmi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2qnustrbk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2urztfvuz.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuxknkmu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnliiyh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucgrreip.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2thoadwoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzgutkjh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2pknsvrtu.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2hudikwkc.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wzovxoxh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gt2spgzzhmz.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqhwelxm.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2hsqzgwfs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxinhiil.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjehanqt.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2hcxsagzc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujcxtjdf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2lliiwjwj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2jufvcznk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2mafvkspr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2ijtrvwbr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2nwjalbsn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2poxudlvo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2itassysz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2jiwucvpt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gt2qnvosvfg.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcfzwqeg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymwghmee.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2gdvibjqf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2thgbwiuf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2zfxuuyhd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2fgesjamx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2zhbincql.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2ecnhpgpt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2pfvxpnvo.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2letleawf.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2ouzvhdmh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2lzmsmbbw.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gt2zfoetjvs.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2clpcocyr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2fhqrpytu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gt2mynfnmby.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2gdmkeyld.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2gdofsfcy.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gt2vuppfirl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpfnqbfi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2htrtxjqc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2hnaxwdum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2peijblqc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gt2tfeldxxb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2fzdcgohi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2csbzfiuc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2yeenkhrz.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rriwiwte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2ftozvdiz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skywjtks.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gimtsilt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2cgvgzmib.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2otvxptqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2fjngnmle.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2lnnzdyoj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2edzndhsx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2nsdnsgdm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2cjevywep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2ffxnoizw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2nxpettao.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2hxhungjz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvilfikk.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmggxpjo.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oghiboxb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2cnheagps.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dwncpisp.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gt2nyvznojv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gojqdanb.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2hknztkin.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2uulwaipj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2eeauphvv.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2qhzardsv.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2rwcsfwop.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2wyaaxtbx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2fponcazx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2yfekopih.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xafzqpji.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2jzuevqki.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2cevfosin.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aknmgdtn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2lkaydozp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2ladetbih.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2umwkxnjd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2ciitnuzs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gt2kscchnjg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gt2ujdhqsje.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2ogrfiitz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2itbirvjn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2xyubnmak.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2zdqbpikh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2ucqmskah.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2lyrppdwz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2rfgxjlss.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gt2yckgsxzf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2mwdfpzju.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2btviroag.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2nbilbzxw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2goaqnwvj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2shnaauzj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2xpieolor.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2rmxwhqck.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gt2baxokfeo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpuognfw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2sjeijsjc.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2obhohwte.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gt2zgtikmci.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2lgccwjor.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2opmqwedv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2wjhoapxc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gt2ebmuyyey.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjpajvgi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2yuvnfriz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2oampqrqo.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2tjxmqtwy.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2svbqptif.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2djqgyhlb.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2ijghemxd.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2odwdpsge.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2xhiprhtm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2spwqukqu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gt2uqjyurza.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2mtrafhcy.html

[L07] 处理 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gt2xsrycxtx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gt2gtotkctu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2zmblqfdm.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2uqhiixgg.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2ygmmbgcx.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2dgnyptph.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2ehgvzfen.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2rvfbaisx.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2vocsoxji.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2wzckqmea.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrvqchgp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2lkyhvslw.html


<!-- 参考信息 -->