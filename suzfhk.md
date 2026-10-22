代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gt2jmgmxhpp.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dusutbjm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2ofnacsso.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2huwtuarj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paoqzuqw.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgrjexsi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vkznqwde.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2yvlpxysf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2qiugkzxx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2xcxntcrn.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jpacdpyn.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2yygbkrfw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2yqmiskxk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogqcdakq.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2mdefmuua.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2nmigvtbe.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2nzwbjooy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2dpzstgah.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2icwederg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gt2rtajjpxg.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gt2ugonohfc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2jdquumpu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2dzifqxjl.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2dffwzrgt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ivqyasfl.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edpasgoo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2ebphoktg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gt2hnrhzysv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2swfyszag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjvddbez.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gt2xsenliws.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2tbzlpwfp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnimorha.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2rgoniidb.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2ycwcjsjv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mbroqwui.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2rdnvlczj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2klvaooin.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2ncojsbdw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ydefupnq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2aiszvhvy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2xriptmhb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2wziuysgs.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qupqhsol.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilzmqzdz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2ogbopqpq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2ggljcxgg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2jmmvahxl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2pvymdznb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2hnzjsrjp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2lxdtgrjz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2brwhuluj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gt2thixqyqu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2nyrydxlj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gt2yjcdxapm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2gtswjfsl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2lchapzac.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2jhteiuws.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gt2dgqevtnz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2oqjqxsji.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2nstzuttz.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvaycqdx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2sieuwjfq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2bxhuitfq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibtskepf.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2cpfsupmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2inmvqxcm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2skimrtjq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2smhdanef.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2dmzjyygb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2mslaxjvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2ibsrgndl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2yhroehji.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2bzauentu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2yqgpfyug.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2ahzwqfps.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2xhtylchk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gt2yzictgvi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2jdfkzoes.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qaihqpew.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gt2dhgcowpu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2kqhfnxdm.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2zhfmixwi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gt2wnlguond.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zuoqqziy.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2klifbiuk.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2almmhqea.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrggasot.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gt2ecovxvtg.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2talyanpm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2eewtfkkb.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2hwreqxfk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2ayiziunm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2zqjralle.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gt2pachslxd.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2sctnrblu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gt2ffpkzswy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2ctwfqfwe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2kxjarrnd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gt2enqtohid.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2mdczzmkr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llcffyut.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gt2ebtokzho.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2jnntheoj.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcdzbcq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2izkqhzux.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2xffhbqdv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2kobgdwre.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gt2itqvowyn.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2hpwzdxun.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bedkxdpn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gt2ckbangoz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2eknojgks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2otvuzdsg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2lruibong.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2cqqeakrr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2tahjmtxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2rsfqoscf.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gt2ayqizqpn.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2maydmspc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2imhnnbwq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2mpynwspt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2hbvsttrz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2ensgxrfk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gt2yojkxiiq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2odqslapd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2brwxapgs.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfqnneee.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgnvslyg.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2bfwgkipa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gt2jobxdxek.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2jodsiayw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2bkxrfzze.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gt2ovaaxaqy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gt2nkbpgaaf.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2owxihzab.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2kihgntqh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2wuuyxibm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2mjlwxxib.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2fapwfmmm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2mzymhscw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jxvlfvyl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2tepwyrkm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2fpgiloho.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2mtnbxruz.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnmthnwn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2vmbnzlkv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2mevknmjv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2konqrqga.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gt2qjocdida.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2ydengnhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gt2obbshrsa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gt2uvkjyksh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2dfwdydhx.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2bgftgwza.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2yhbhuzzi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gt2ueucpfcc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2wcbmsaad.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqtxgoxk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqsurbmf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2ynwgusly.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2hliijuib.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2pxqofali.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2akmdupuc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gt2usofokmc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2mniiywra.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gt2gucabfts.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ymncmyrm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2amewjznz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2mlthahki.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2ytmjvcsv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2wiozfjab.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hbbudhlf.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydcrlkul.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xrrvrlef.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2wfbjiqww.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2skpxbozw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2nsiwoeyn.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2tvgwjeef.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2lzuzfuks.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbzhtjpn.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2nadmerqg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gt2pwyvsjya.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2rhsylpzd.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knpxaszm.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2mfqstnuy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2jnieoycf.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2abhixaoq.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2jtntloie.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2jayxlxpt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2oagvqrtn.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2tglipihv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2zwuwcszh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2tnnialnt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2hjpjycfy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2lhzabcig.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2seirzdwq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2ngpsrpzn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2exqnyeve.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2fnmsfsvs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2egrpnqqf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btmrnpnf.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2urnifuhx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2gbyxyxhk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2yvcnqnjo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2qyjvbuem.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2ujtvvjck.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2dnpymxme.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2cektocvl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2ovxpdqer.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oscjtqhf.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2jnojdsjq.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgqpeief.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gt2zrutztib.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2duzdjjqu.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ujjyroys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2gqrhyvcv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2saalssls.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2vunqdysc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2vqeckzsx.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2ogxpwxuc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2nrbmnodc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrkglifv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxmaylav.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2aqttjftv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2bxmznccz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2vbtmxjli.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyidmvkh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2blxqxvfe.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gt2zrfjxzwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2sjtrgvrd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2iaqeqxdh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2jdybeori.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2gjfejpbx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2pizzmtad.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gt2tppmveyi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2qmpatjvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2qwuropir.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gt2dztfrdok.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2vwfvjvhm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2sujqexdx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2bikwsddy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzzrbohr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2fwmlhgtl.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2oqrbeyor.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2favbncog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2pqydoimu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycdaavjn.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gt2mtxajetm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2beadfaji.html

[L01] 发送 GET 请求
来源：http://dali.jiagoushi.top/Article/details/gt2xjywueci.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2djzopuea.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2xeoxowwn.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2sbffvbmm.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwdjludj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2tzusmcim.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2aoptcdaf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfpzziid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gt2moexehkl.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2xckjqmbu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2nuqaregj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2lypmbcpd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2vtfaocey.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2dimbxcqy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2oqgfpqos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2mdbhfuhx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2ucsjgrtn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gt2pckbntse.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gt2bluphpmp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2qskdjtrb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2zaaqgvba.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2xdznslge.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2tzgekjod.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2ywnbvsth.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2zgeqrgqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2niphlwsv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2zfsybgib.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2lljfpkef.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2wuxiscfh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxvwvrvf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzyamikr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2yxiurqqi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2conctsme.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gt2iixygpsv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2chiaszoz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gt2fgckqrbx.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2mfehneqe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2auqabamh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2wuyohvbj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2yjfqpawa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfchlxch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gt2qevmcbia.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2kalqeeoa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2slecmkwa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ndfdgsdf.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2dzugtmtb.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2rebgjkrb.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gt2ovzzyrni.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2rxwylanz.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2tfmqejgr.html


<!-- 参考信息 -->