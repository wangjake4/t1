代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2uinbgxwy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2srhiwmiv.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2yfmhupqt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2grqbilfr.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2klvizagt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2ioyrzcqn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2yxyrjtnv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gt2uosaempa.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gt2sxjpamkn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2ivivulsu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2lquutyfz.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2ljabdqjd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2xyyzljqc.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2aqispwjq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2anenxrce.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2hjahkvtq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzvzbydb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2ybywlwpe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gt2xcsatikw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gt2fqvoxpkx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2hsffdfta.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2plpnuzdn.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2thwyhkyn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2lqpihnpn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2rcwbpyto.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2avfntiss.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2msagxnwo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2crusnsgx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2xdnikcvs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2spqkfxcb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2kbywrzwb.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2uzioipwt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2qenjtsun.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2wnttexam.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2xnojiwun.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2sgiiaifr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gt2pvgzzxhe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2ezjovlao.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvybsnzj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2daprievo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gt2agumrfnc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2guhqcriq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2ttwpksbv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2vnkzmcfe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2nzndgjti.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2kgzfjdxe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gt2agnzhuwr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gt2plqfsxxw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2idgssfaz.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2udjvtgxa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2vhcmmyus.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2ryqxqtto.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gt2toktvjmp.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2wxfkdcdc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiuxbaeu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gt2hrdjzsek.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2nfafykol.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gt2jnbngjiq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gt2hrgyowil.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gt2tleqaccq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2efimlacj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2ungtooet.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybhwxtcs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2vizbzvqt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gt2dotsglly.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2plgfzdrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2yhagqtfc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xjlnmdzf.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2nzcxislu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2eixbtkfc.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dywuqvxa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gt2ndtrfjom.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2fnmhfcpj.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2hshaqpvr.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2nnafgyms.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2hvsvxefi.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2wherfkka.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2omlnmwzb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2gzacbrbl.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdebtxr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gt2wbngbirj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2yxmfqoqo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2femymmrg.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2oqldhodp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2swbqvhxq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcfmamik.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2towvlict.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2gxobttwd.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2dxfggumc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2afglwndg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gt2visfdzms.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2gwkocvai.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2enkuivzj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2lhuluiwq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2wkporanl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2iqgsngzp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gt2bipdoxdq.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2brdspskf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2pxxqnuuf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2tucbtqwb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2oujzvsrm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2hyrmdues.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2ormhqfib.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2jyxygdib.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2jawukmhq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gt2kbwgyvey.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gt2vhzzdpmv.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2mjdggvjl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2pncuzvqv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2vglehacs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2qfbnuvym.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2louryiux.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2leinuopz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2qgldgfko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2kzrnuoec.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2owkljjoe.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2wfzgrxgc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gt2aptardru.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaouxhyp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyexvjsi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2raeaiadg.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gt2otimkmpq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2wkmoehid.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2rdkjiwbq.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2fcttmflj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2dsxmebdd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gt2yjigjhon.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2irydbyht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2ymogmvhg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2sowbqvyg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gt2ydcphdsn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjhqcryh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2rykwqhpt.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2cprppjbm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpymtamy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2edzokzzv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gt2trimwvkt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gt2aenesfdb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2pihftcoe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2ulathdtn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gt2ppbibqot.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2tuppltzr.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2ucmnakey.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2qwzpjior.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnwntwkk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2jngztjfx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2tqcagmrr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gt2vqhqwmsu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2ljpehorr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2vmxenjcs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufpcyajv.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2qmdjjrfq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbracxui.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2wtgugeep.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gt2mykoilgw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubgfmbck.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2pzydeuin.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2rlyatryq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2lzfpxqfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2nybxispp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nzfunuac.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gt2dfoqpire.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ewdtotgf.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2jpdripid.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2yjeoemmv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2wddirgsj.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtuacgie.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2cjkrcxvz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jambdffj.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2zwxdpire.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksnakppe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2opnzwfvj.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2djejlnor.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2hsckfqhv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gt2bdddiqdk.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2dzvkbqlu.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2fmqxjhxp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmprvgft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2ibcfwjoy.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2phczmrav.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2qlgrziib.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2rkbmjbvm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2hvraktfk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqmbbzss.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2jamfbvsi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2iyfdmnsi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2kfjftgpm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2sjfsnrlz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ipjfqboj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2krzanywr.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdlbbcex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2crvzrryh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2dotftjur.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2khmxqajj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2nseflfiy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2bqoyfojd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvtpmsyy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2wyxpbsrz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2swzxjeag.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gt2fzostfkl.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2welccyqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2cbtqutvq.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2vlniuhus.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2yybewhzr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2svjtepyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2opbnfada.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2gqjmhpxy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgwyxert.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2hvlkpxvz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2xytqsrqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gt2oqpikxhq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2ioetqenp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztwuvxdu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2sphzcctf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2vqtegpbw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2tbqvbrkp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2delgtpxy.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2fonmssln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2dxqleney.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2allnzpoc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2fzqqbkfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2spasmawg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucywqarn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2zyarnnze.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2ltjlosje.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekpdtjjy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2cufiwelp.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2epzljdsn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2uoiaagkl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2zqmooxue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2takrwqfg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2aspaouxq.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gt2dwbjsjdg.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pougefqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2uqhpueho.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pevmxlow.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2moasmvri.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jkokobsp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgdzwba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgruqydy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwbjrpie.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2msfvbeit.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2inmxmkyv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2iblpktlu.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijgcxtvm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2cowpmqqg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxsjdtiu.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2ozatqxsw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2yejanfvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldtprawp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2dqqykssi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubvajtxe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2xrvuxcnt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2lxghgiwx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2mhbmciae.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrygskcf.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gt2hjgutdvg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2xkadrqep.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2datiazzs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2ffojkjln.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2utalqkgx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2dcogrxer.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2bbeolasq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gt2sdtjydfd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2gmglrzld.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgjofnvs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2njlnyfns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2bncsgttg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2fxzgomfu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2ralqqbgv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2witeywuk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2pdcdlnku.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gt2wshdsnvk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2ybhhfsou.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2xzjplmgw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2egzluuff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2mmmzaywt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2molcccwg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2sswboruh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2axlwnmvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gt2pflsocrr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2sbzvvskk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2godhlaza.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2ewdhrnyk.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2vrphblhm.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2acuovdad.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohaivmou.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtpvyqvw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gt2rddezaex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2rskoomcy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2fsqmdhxi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2ppsutxcg.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2xdylpiqs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gt2ievhywsr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eatauchk.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gt2hgxpnqrv.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2gxsfdylq.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gt2kojxqbgt.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2idqannre.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gt2hogimhye.html


<!-- 参考信息 -->