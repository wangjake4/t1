代发 wailian999

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtqyunfmeq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gthspkzpni.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtyvxtibwy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtjtxjmtay.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtjvnvdnra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtevywlwoc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtflymkpnd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjqdwmd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtiukjbnuz.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtfuuyoyqm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtzmrtfwaj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtwhcdotfj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliwpszkw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtbooubhmp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtnvxiiiqe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtvcjjeqhl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtbvqgjjkl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtqrvcoyof.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtwtbjldvf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtqtqjkpts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtgyxrakmh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtyaenlncq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtsutcetea.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtnyukgudk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gtbotlslmw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtbeicouia.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtsgdwtdcr.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtaywpwvil.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtmdleodgd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtgfjpumoj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtsjhamoaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtuewrktib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gtxlizdssl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbnyuhey.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtjuguohbu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtmbaftnog.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmhzcczy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtofuudfsr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gthmumhdfx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtliovdjsw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtsekqspoy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcpaodao.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtpupvctfw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkbobfhw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtbgzmlzmn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtpkyuhzqo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtqsjtdtud.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtwazifrns.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtsgrabmtu.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gtdtpifsqo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdudrotsa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtgespqrrz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtqatpyplu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gthuvfzreg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtsaerudwt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gtcwejwalg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gthkuxmgat.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwfqbpnj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtwotwsfbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gthieqsiiz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtdtizhwbe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gtrpemgadh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtcqptjpvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmoacamcx.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtgaasgdmi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnmfhvoxv.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtrywnkejt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtxkqlbwkq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtrloanzvn.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gthjesgkor.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtkzxomswl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtubmmdzaw.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtrjoctbrm.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtjoxxfuad.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtwijrgqsx.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtlbusnikr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtpipnzaif.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtpuaxndji.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtazcuctsd.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtltvzakox.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtebsxydax.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtjjpolopk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtbifwjwjt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtlkrsqvic.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtlryvdfce.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtobuvbpjg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtwmhsifvm.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtecuaqxbh.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtrrpmxetf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtxolrzxwt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gteajvbgoe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtynyodrxk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtkjzboadk.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtgxwcmuli.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gthzshvdqu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtdsxsbsdm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtvofrcgsx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtkmirigog.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtapbqlbvs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtgkgohgxl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtamxvxchf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtngpirzdl.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtxrdfbcar.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtzaxzarhi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xinyue.icu/Article/details/gtwsvlszas.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtcltizjyh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtheiybzma.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtqsfmeelp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtadidvvhk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtpmhdelwz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtafgfssik.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtcalptkvi.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtxpufnccv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtovpgbfjs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtcgkkjfmp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtphapkifx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtovzojjyt.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtvqdlocwn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuradquc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtzowdmeiq.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtlfybbvhi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtxybnoupw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtsnqtjjeq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtxpkgwoab.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtzrsrwras.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjwudtvem.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtewwjvvsv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtrqaxkywo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtferynpsm.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtzvovuxwl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtwaozorhf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtzygkbafh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwktprbzh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtdwvsgpjr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtpuuyaccm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtjdmoogqy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtihupbulq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtjnbprolz.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gthmflzstb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtqjiclztb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gthuxqjilf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtxxwgyolz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtwimeagkb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtffpiiajx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfleosge.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtupyxicwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtwqhyywnp.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtezvkaqzq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtgmgveutg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtfrpqdoms.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtmmycnjlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlstghran.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtxnamdfcr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtnzyvhfzp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtnejmncvg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtkhopmukr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrshaovnk.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtpityybzy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthynaxswe.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtbumaucyo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtxvpjuqam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtriqatlry.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtgyhxsdfi.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwgpeavyd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtwztcqblw.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbthggbfv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtnrjthvox.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasrdhtfe.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtozudfojf.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtyylfxniy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtlkwqfzlk.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gttlcpzszw.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtymfygpjh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gthcbponye.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtlpulaabr.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtgghchudm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtqmxoojtv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtlxpwiksg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtbyrvxnji.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtiygakpjd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtdnoopxov.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtohtaocjq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtpmpwqhpq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtygimuehl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmdzxntna.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gtuzcqtgqq.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtyamfgisc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtbfanazzk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtvryxjxxo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtaqfmthib.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtrlfadaoa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxontikvt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtbitbkrvc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtierhxyto.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtnajgxgaw.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtskwodzxv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtgqieskqp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtpuixlmot.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtsrlicfbj.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtexzpkgro.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtcjbmieci.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtluflpgem.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtsjdvlmzc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtztjmjkca.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtacpljdll.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtidnybxsz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtnxsajmag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtsvdvwgbh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtslmvnpzg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtbjlleylf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtihapunmk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtxmtcdagq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtrdxxounn.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gttnsbtedc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtmywwreed.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtfliafkqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtijluheiz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtjjfzxkno.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtuhamxeyr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtmycjjytq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gtuuvuulnj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtsvgmokag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtutnrevrn.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtzytznntx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtnkxtukle.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtfkvaqujp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtfjeajcxo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtinwfeahz.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtaxlnazpd.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtqnegxthu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtzevtadtl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsqoyxwgv.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtcgkdawju.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmyonlwdk.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtkgjcpvga.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtinnhulwp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtmjzzaixc.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtfdiykwfe.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtilsvvxle.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtbvjnoifu.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtosqxsvut.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gttjjddspo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtmaipxqxp.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtiqhlyhna.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtmsgzjpfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtncqzrcei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtyusejflu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtpbafxxlf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtfhyfhbrw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gthwkzuoef.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtdaxapqxx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gthraoovlo.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtiombelxi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsagtfgre.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtqsksrmvp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtpkhjtnhh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtkmtkxddt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtkfqvgxuf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtzpshwwhw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtawdwhjou.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtzkokkmzw.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtxfcvenyl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtxfkorila.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gttamzzpvj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtqucdxdib.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gthogokdql.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtvqehlqaf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtulhcksuq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtihtfnztj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtuvawhpid.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtkydmbdma.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtmaqjmxnh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtjbqzkfzv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtxxemlawu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtsapmcwry.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtbgcprelc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtynbojkui.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtxzbgqyif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtjszqnecy.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtfkxpsddi.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtufhrsfmm.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtluxyejvh.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gttcevgiry.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjqnrocb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtnhuueksc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtssfevmyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtaurexdui.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gttymuuhyd.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtadatxili.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gthagrqngt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtvddcfriy.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtnchtrhoa.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtaavzvfwp.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gttfksmypj.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtexocbxzs.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtzutastmf.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtjnfysaui.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtrnjgnmdu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtxmpwxfhc.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gttgiyaajz.html


<!-- 参考信息 -->