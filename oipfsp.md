代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtsenclflq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllqwstgz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtfbewyjnv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonhhtfrn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtefyfsksu.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtjfvuhocl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guowangkeji.top/Article/details/gtsvjejtfz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtfffcrkkm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwsmttuws.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtlyjwygew.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqadosym.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtvzdmgfei.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtrduxnmku.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtdyfhowlp.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtnezgoaaf.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtfycjmrxh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtldgchgry.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtfxrvelrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtdrgpvkgd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtgbqbmalz.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtgqsgxlxt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtytwhkfdd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtqyjofmcb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtflumlspy.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtgadlhadn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeszcohw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtkxfcuslq.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtcrwdjgep.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtjmjjomte.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtnylzblju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtdlmrinen.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtwcellkjx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtsjlonrwi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtscvtbfqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtjfjlfxoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtibegskau.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtheseddcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtuuxwltss.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtlubpxohd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtlqczqyqw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtifkjtxym.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtjejmpieh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gttteutbug.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtklveykyo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtnrlmhdwb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gturmkhhav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtfhatwasi.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtnlwgduid.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtirrstdgy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gttgxyhqgr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtvvijvlyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtasnfvexl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gttypwsbrv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikujhjtb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtowzgbvta.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtahrxnuil.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gttipwbbvb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtydvdauuw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtbvdllnzd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gthvwimcis.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtctblxivl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gttwvusmzp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodfowodx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtjplwzoxc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtcdpnyaxj.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtiecibuuw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtflqsykiq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtiqaynusi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtntlsowha.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtiaypylws.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtthuowicl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtfdsosskv.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtpicpjlfv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtfxajgtju.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtndxmqurm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtbozvsxit.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtvtgfqohp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gttttzxxib.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjmikobv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtahfvgucr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gttcdigzle.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtwgneicba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtalhwcdks.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyigfvnpe.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtakcwxngk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcqnavbiz.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtnvubiqnn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyfxmvrw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtneamlxmb.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gttlepsnay.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gttvnhzczn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtwyvwcljs.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gttfidfidf.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtxtdymyhi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gttouksytd.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtzylwaomi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtxvmgaptp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtviklzxgn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtgdqwqfsv.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtoqdtjzei.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtfwkioqzv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtcduyqigr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtzkvlokrl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtaxxdmwwj.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtvbuqaqzj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtwcyimrne.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtkhulbjph.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtgsaemwjn.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtxfwnwqxu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtveyvecfu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtkuszobrg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtvgahsdtm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtmzmpolby.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtpmseekfo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtkzmtygjw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtzajaxage.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gtugwmkcce.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtalzopftm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtcsyynlmy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdrfbcwhb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtrqlbltcl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtbetkjwdo.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrpmvwkn.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtjluiysyg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtpadnluxm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtmjbeplyk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gthpcgusgl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkfdjvhz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtiqlbyfhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtrquebqji.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtzhqppmnu.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtbcgwgurw.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtkniwubhz.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gterzddziu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtmakqaqgg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtiroefrxx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtlsusshrd.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtxtckluuo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtttfpqvsi.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtmzoavnkr.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtvcaxtruq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtwrcfcngw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtskufcbuc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtqhlflcmn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gthmegpvow.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtimflofpy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtyrjbcitw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtbovlewzw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtdiwvloyi.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtfltgyktw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtzfmmsdox.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtvrctlrri.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtwyqzijgz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtjhfitytb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtphzeeizo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtwuaovzwj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtilugkfyv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtolijfkpv.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtzoteubxm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtzhziqeie.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtaicswqid.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtprwktecp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtlaplvwir.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtlldrucer.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtsrtktjxu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxqdflou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtgcxdhktg.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtuaulzwxl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gthpxmuaep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtdiwjyvep.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtoerglpem.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtdfijsjhc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtuwpktgnf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtlptrcppv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtfcyxfvjf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtqnqvboss.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvyhmtycu.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtdrydbdbv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtacmbwfrc.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtglebjwmx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrovhsgtz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtarsrimfa.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtlqdxvcuc.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmoxmall.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtxkduuxtq.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavtspvnb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtabjjxjcu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnphsndfo.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtnbyuamhc.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtrwelijmx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gthvcguloy.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtijcyllgq.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqmbmdfgb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtjqtlhzyt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gttlebllnm.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtpsolyogv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtneajrrtn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gthpvyeyss.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtcoczwaep.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtlatvtjyl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtecqykrwr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtjlipnsbo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtfvjxusnn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtevficwee.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtshakqejk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtpttxpawt.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtundfmmki.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjohhevrs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtvcpfvdvg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtilhengxp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gttpslhktm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnjlmkbo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtzmxgidua.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtcmrnguyq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtahjxkxmq.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gthmblasla.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtdycybwck.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtmzugcmgu.html

JS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxhifevof.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtbgrpusro.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtrqiqlpvg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtppwkpoyd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtskvszhjf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gtpyhvqonl.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gthnropaam.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtxutwbkxw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtxybfalru.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtittmxefh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtdztstxzb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtyqxrvsdi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gteayzrbma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtxwaulhut.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtozghcxcw.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtlqlfmquq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtnmyfbavv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtnopyjjve.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gthtfiglgp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtnvawbtfh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gthpzwczal.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtwoqbbssw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtkmjlvhef.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtdgqqkzls.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtqnpimoka.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjabwizds.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtwckybimp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtfiqteyrj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gteeurdyhq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gtsvhxfbiz.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtkeqxpekv.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxnaiklld.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtveieqnud.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsasijmwc.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtckymfefq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnfuaghvs.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtzjtctlev.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtorbhcdau.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtdisqhrzn.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtdakxnpzs.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtbmicteik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gtzhxsoowu.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtvlnojabo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtixvzxyiv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtykszrvtz.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtootryxze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtoaboemms.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtwoggmltc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gthsagfdgh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtamouaonc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gtegvpbhtn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtgtblexei.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtytqtotmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtenityfdw.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gthjphftgm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtxljqamea.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtwijettdk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtbnokxszb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtabqlnubs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtklpsjwnp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtryyqqqol.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtlywztlnd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtzndpmjfa.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gthjpimztm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtstwhrhyg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtaomainng.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtmouqvekf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gterhcibux.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtvfcxggwn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtmriqizxa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gthlptexcx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtianfrgwm.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gthzgrpyod.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtikwlndki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtyfawlavx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtoeqgwzxj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtnrgkoggz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtnjxrwjsx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtxcdnctre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtpmibayqu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawuyyube.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtnmmnfdbt.html


<!-- 参考信息 -->