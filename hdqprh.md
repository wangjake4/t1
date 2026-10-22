代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvvcsvgy.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2gtfavjfh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gt2jmfyekwd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2watubjgf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yroafdue.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2iytmppos.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wpedxnjv.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2zysfybun.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rucbzukj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2kjbmflju.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2mgfxgcne.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2cpueahsl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2pgpxhdlf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2zzdpwgvz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2cewbyldv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2fjaodcxa.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2sxmipxlb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabigqrp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2pkuqlbqo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oknnedtz.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2atoilnkh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnevxuul.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2cikdojqg.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2mgqdzfkv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2jghqkunf.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcofqogb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2spntqqeq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2xnllfocy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gt2cmveddwy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2bnwrwsgv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2fxstweco.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2idvnjqxp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2jnmhjchh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2gzgnyrkb.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwuuzadp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2znvpepwb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2afqnhonn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oadjryxz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2dqmheapa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2omccygnd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raxdounj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbnsteqg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dieryymm.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2xdshisdc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2dtksuwpk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiwcgshm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2jyddfllp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2ahcprswx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2ssnfkzds.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2luosxmcg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2inqztrxh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2qvpxrobw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2qrwcynxo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2czmucirh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gt2wfqmvuuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2gnbpnfqx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abelubuj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2hnslgane.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gt2mqviyndp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gt2oionvozj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2fapkcxvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2uygglxuw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2igqdrhnf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2ozgsedra.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gt2jlkdwraj.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2gbsleqhb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2blnturuy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2zybupyqd.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2xsplvqwm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2rnrqghcu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2vkrodjuk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2epvhsifm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2gutcbjmb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2deprajhq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2eczftylg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2lmamkfbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2gszjlimk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2mlcmjjzb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2tzeppasr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2igvrwtiy.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gt2gbxmhnsk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2tqcdoiqv.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gt2vupmunos.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2pekrevnt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2olhjzedr.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2vsaphnfb.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2vwaykofg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2fzllkhhu.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gt2firgvbtq.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2xjxipdfw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gt2askcqtws.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2syvrqkxv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2gfzjmczl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdyxdliv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnvnibpv.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2ltjcefeo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2nebachau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gt2ovmjnomm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2avsxbgtn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2ymadotni.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2uerbmqmn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnwltdzr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gt2tktpjbvy.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2sqyfpaxp.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2qhjnctbl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2uxshtxrt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2pryovyhj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2lqavsfvm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2lcrvaace.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2mktsxaul.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2ezktogru.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2zcwelxou.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vyonsdnk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2vidnnikh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2gmibkuwu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2jmzgdfbo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2majlvzbq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2yyyvsaqn.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gt2jcsdstej.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hygljjoh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2brgrurby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2vxsjrxfm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2khhiufzg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2evvqxacu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gt2cnbxsbkf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gt2fpqfushx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2oiqqpqbv.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2qgbwbaio.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gt2qatvhusw.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gt2vgrelmjf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2zduoyntd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2hxukgknr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2lmlmrifv.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2ifvqjlow.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2zyagbokd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2eupxhfnt.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gt2pwrzwglg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2domtdayw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2nbhmdbsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2ldyowdac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2aslqqahl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2ieygpbea.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdzvovcp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2zkzrsfbg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2tqudnsvk.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2fhnvbntj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2cqvaqstn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2augagcrp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2pgyjgzow.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2zsntxzwz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2mgqllpbx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npxywmzb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2hkbfpbkt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2tiyydtws.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2ayyjhdtj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gt2pxasrqym.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2pxdeczpw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfncpbca.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2vvtkveir.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2vbiqgmmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxaibtmj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2qiqtzhqh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2jqhblobt.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gt2rpxzuqun.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ttjmtkjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2gpbujexl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2kleghkjf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2ruizpihg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2qvpdfbwr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gt2owqnhrci.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2ameygxcf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2mpmiqrjl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dwrnbpat.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2fpctrkfy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kntflwnn.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2wknyjyyh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2hxikwsdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2swzhctxr.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ecgzxojh.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2etfwihqx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycxsuoay.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gt2zvlkkijn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gt2skhovfuq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2fwfdkvmj.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2igyqyxok.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2grksqqlw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2meiyffrq.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2uzkwhuvf.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2shnclosy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2rciwzqbx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2byegmdsc.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2eonhqlba.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2pkqnojuz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2nfqylcmb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2teijfjzw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2gimrufoa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2jitbgxfl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2dtrpyili.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gnxxcatn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gt2mvyqjuuy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2sqkerhbm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2zevzxkkp.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2ymekxjbi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lezmooai.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2nmpygdtp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydfbqyhn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2nbgzwnrh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2gitvqkuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2sduszcre.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2kxtlhvdp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2pmdegsoi.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gt2rvrqvdnn.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ztolxcme.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2qpaaehiu.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2bdrkaivw.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyhlcmje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zscnffcv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2cddwnjmx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2etrgyzwu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2isqadmgx.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2uiwlvhcn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2qwtgzkwk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2mrclajsk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dapnftli.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2vxxzuopt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2gzrejuts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2btyxxrti.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2hcejsycv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2nqpoviax.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2iqnlkunn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewvozrga.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2xqsyhnme.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2djlsraug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2trlwvocg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2hdcwxlqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2dpotikwu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2ottpctpf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2jkohxxal.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2vlceymnl.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2bcikflge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipqkjrvn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2xjalhzkz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2nlykyntk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gt2anvjmboq.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2oskncajv.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2hveefaiz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2kqhxogub.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2javdjkny.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gt2aopbrxbo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xscjmwog.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2tgvoeaoq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gt2zkopavkn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2riroozsy.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2goowkwem.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2riskubid.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyzwnpxu.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2iunfrnwl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gt2ctrkqgrl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gt2goldnxvx.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2wwxsmrav.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2mwvtfkhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2zifcfgjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2uwqpqpxz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2wwsxqwbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2fktekvso.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2ggcmjvgc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gt2qjzjslmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2fvvukdpa.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gt2tucszdoo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2iamyvazk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gt2zcztjkyt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2svhwrukp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gt2nwkvjfjd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gt2kujohpum.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2cqhkfcds.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2ocrwcrxw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdmedvyc.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gt2kwldpfhs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2llyzunnk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xboekunt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2tszyrtuw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2ggyumlvg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2iiygdqzg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gt2hkjzsiyk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2sjlalcvt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gt2wvlpnimc.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hacjsqrz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2rhfkrjfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2skcvwklc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2nheolzga.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2isfjqoal.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2hbbgsesd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gt2yutciwkp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2axkwlpth.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2hrycebms.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2rtifhpcf.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2twtfvsti.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2evixpihm.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gt2cfoxxikd.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2wtluxccv.html


<!-- 参考信息 -->