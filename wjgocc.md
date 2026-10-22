代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqkibsmw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2wnizhuox.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2yagidpuz.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2mtgjsoui.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2bhqmgbuy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2ejlfwyff.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2icndzekt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2massxqmc.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2rhthkkru.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2ssngwsli.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gt2ssbvuwpu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2ybszgtys.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2mdldsjku.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2vdackigj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2fjeznyfx.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2heoapmfi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2nmdvksvm.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjwhktpc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2vduvqvmc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gt2fppymhfq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbzfvgxu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2twrpekhl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gt2jsjfzvtq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2jpqvxlur.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2gzzmzcdk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2cqsgbyoo.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2tirjixpj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gt2ppdkcxoi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2zzhskdff.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2odtdzyrb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2zqzofdzy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2pwtjsqxs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2kqgemcnt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2pienfhkf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2etfknlad.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2onrmejka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gt2ounhrimh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2klfcvwsc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2hkswtxdt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2lxcdvqpx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2idjvtwyv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2bzpijnxn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2xtgntvtf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2xhphkfjh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2vwdimzgd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2bdfwwaxq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gt2vyaddcyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2ximbfogo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2isxuzgoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2mqpzhkiq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gt2vsvddalh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2kfrhhtak.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2mhsthhei.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2ekclthed.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gt2ehusgbnm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2evibaiek.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gt2otgyirkm.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2vezbtwoj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2sysqjjqi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2hianjjou.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhcbojpm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbfzwxwt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2ugkuxssj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gt2ndsvjoys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2czjetzoj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2ldxgxzfs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2iwyokdiu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2srpednmn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2wgazkccv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gt2fbuzcqvb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2vbmnqsjl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vhegmild.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2efzkzbor.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bhogkjai.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2fzhddwbj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2vqqcfsas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2irrtrcgj.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2udfeqyxb.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2dueihmkc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2qbwfjlfo.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2jjcngvlk.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gt2tsctqjyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2huhxjklz.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnmkmznx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2moqppbke.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsifambq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gt2oymebhoe.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmapxemv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2ruvwjvjr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2frgwpysq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2cmmciupa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2bqioczzg.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2cthwplif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gt2wpqxsvqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmecdoxp.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2tcomnpmt.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2guvqpvvo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iweyftrw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2gdnbcdud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2wyubplnd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2xxdvxkjv.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2xdmlqjuw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2wzvphtnh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gt2vswkhtmn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndloauas.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2vmimoswf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gt2nnnrzsmn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gt2juyxqpyd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2iypruzhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2pbqqksub.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gt2wwomrixq.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2zbgrmexm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gt2tbrspish.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2ozyegzkn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2gyusmsto.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2zezasvcp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2xjtswstp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2ihrkrwxm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2fkrullaa.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnzmyzix.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2qmkyugqu.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2ygvhibny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gt2xpgrymvk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2fsoemckz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2ietygrev.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gt2bnwwwxaw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gt2rmfvlkhy.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2ykjpajmt.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2mnemhwdq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2nnfyjrfh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtowpurn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2asbicrkd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2vwnkqfll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2mifrawkz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2atpysodn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2fkegyrme.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2dsktoxws.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2ofmdsmmn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2efytbexx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqkqrsdh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gt2sfmprazn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2sqerwbks.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2yxndchks.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gt2ehbdftqr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2oibjpcrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2iwmsshbu.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2maurkjfx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfvfaxvd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2xllpcozq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2jsrtplbz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkjrszop.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gt2vdxaikbd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2mnlwznrm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2exswqhuy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2wwwjsgfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2dsczitjy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2monpsffy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gt2fturygqh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqmfonly.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luhobwnw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2kddmxcyt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2sealcndo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2bgcrcjik.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gt2vizowdgu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2uofaqarf.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gt2fkkibehx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ynfagkkn.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2okezklxu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2heowkkah.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnqcvprr.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewufkysl.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2eywqdjtd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2wuztxagl.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2vxrfxqlq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2cvnqiwfi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2urbaapcg.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2kfdoswgf.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2gszgyrze.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhurxmim.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2paerahij.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2bxoigvbw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmcmyrpt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2avmlegds.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2sftadcri.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2hyukirpp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2oszrkuwf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2rdigswrg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sebqmxea.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xerxsuit.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2emfacyvz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gt2lsjanmza.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jswfgujj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2miggmlpf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2sxpfenxh.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2jegjtqoy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gt2tiohqxvk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2hwoocebc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2qfclpojy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2wwklvzza.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2lqmfzydf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2bbslmetq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2cjqlawmu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2vmpoqqvu.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2xkyiympi.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2qxytnqbd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2exztitcg.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2gcsyekil.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2gqdeligq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2eauxifvt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2lsltmcll.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gt2vnvowsnu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhhjfprd.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gt2vdkmewgb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlssobeq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gt2mdzgtqae.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2ldgjynry.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2tonjxhng.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2hkcvonaf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2mjvftuwy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2cvhsxxqf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2cnpdddit.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2icirgavk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqfirlfh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2rgdbvdpu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2uzxwunez.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2luexudgs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2oackmqoi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gt2ystqjxyz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtxgmfdo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2qmhparwq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gt2wycqacfg.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2opzwmjwr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2dinlbxas.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2ehqsxbto.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjwmsboq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gt2pebealyl.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdnkivgw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2kpjrrixl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2bjimvhsy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmqhmsdx.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gt2kaikpupy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2njxwndqf.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gt2ufaoitog.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2nxztbpkc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gt2ovegwkbo.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2tqgvsmxo.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2biwmcfbm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctlppifm.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gt2dcxcsvtb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2pkgcbcdp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbhahnyv.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gt2cjakbcrj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2jsqgpgqm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2yzwnaxuy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2ulyjdhgv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2lgpmvpmk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqggvbgc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2prujakrp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruqtztqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2vxhquzcf.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gt2ccydvszu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2wqrqhssk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2smnppmcc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2vnuhhjov.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gt2ubiqvdcq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gt2rvyrsyed.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2dotiuqlb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbdphagd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2acogccvs.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gt2npeeqeia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2qxucfzuv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2roojivzg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2dzrzegix.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmejhzuu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gt2cilykdyj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gt2dhmzxjff.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2dzvxfvuq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2vpxezjie.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2zdavzntp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2xllrvpfg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjinqdtj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2jomnufpk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fznvoevc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2apwnnayi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2zckhxzcv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfcfftb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2lblensrf.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2xlyxeusp.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2tkruvupc.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gt2vccqmogw.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2euxfbcfk.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2fpuizena.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2jefcfxrz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2dkbdshcu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2luvbtjxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2qqgfiagt.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2rtxtwerg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qicraizp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gt2lsynjpfr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2xgpseqcz.html


<!-- 参考信息 -->