代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtucznpwbj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtxowuuvjj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmulrbbf.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtiyckeytg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gttggsbpak.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtepvqceib.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtlnjwdudw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtrabsiswv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtqpxgcltf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtqxxcaztf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtigolmkut.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtmevdljxv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtbalsrbxp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtxyszdqnn.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtrfhysijt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtscfnlzwq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtsymtepur.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtdmoyydli.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtuzqyvyii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtphsnnkru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtdzjwmihj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtffsesaoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtzgetaulr.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gteclcqfiz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtpfdwbysh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtbealhjnd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtzmcevfez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtztdjkemu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtzpfpmtin.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtvbrjsmuh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtcrqqhoxz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtehbltjrp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtiagkoxxg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtqpelavbq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmvvghyb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtwaskalzs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtxairjqor.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnosfidm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtmlvochvq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtqntjoyam.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtoixdsomb.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gtglbxktmj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtspomxqzm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtuamfhqay.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtpstkwhdq.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtuglwityh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtwikscnmr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtklizzryh.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtrjjrosep.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtaezhrqeg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtktelmgtf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtwsffejlv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtqflwgmgb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtqrwikkjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmasfurij.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcaiomeo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtzbyshbmh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtjdsshziq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtwkgpzrta.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoqhgiifh.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtolxmuoot.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfhjhauho.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtwmmehygr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gteriovfni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtgxsxocld.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtbqzagpfn.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtclmksdpp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtjkmdxawm.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtvwcfdbao.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtfharrxce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtbpcnuiuw.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gttubdgvep.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtyucxslbn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtpqcdttaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtkejqvnlm.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtczgdepuy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtqgqtnzsj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtsxkuvjfo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtkjlperkb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtszdfskuw.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gtmernrytn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gtzlywsdaa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtbonjarrk.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtjralihfx.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtawvkphec.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtaptshrcq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtrrozpuak.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqbvefwc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtwnwgaglx.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtgsbegszt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtbsolholp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtkzoyqjfv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gthckhsmbx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtknlvrkxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtybcvpfxt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkylzaoed.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtwphkpjxh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtqibnflni.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtvwcqovtl.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gtraecepma.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtqbiybiza.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtvbdihtli.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtldjzwhjq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtgaovhfod.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtptqqwbkc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtiwxywlxk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtttszkvca.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtakeiogbx.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtftithtkq.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtelutnsjp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtoqfkekxo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtifdcyluh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtdesmcghd.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtjprxcpnr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtxnwyesgv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtkbjujvgz.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtvnotqerz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtpdenjacy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtcpawapac.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtirvrldth.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtymtjkefj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gttnvooqmo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtyeidxwsx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtlrpmjybb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtoajikhqb.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtyntgzbti.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtuzfmemec.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtwxknczer.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtndpzxxfj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtzriziiwy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtjwxyjibn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtlnerphno.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtbuufdgjy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtedfmjjth.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtdqyxxbua.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtzgqbrush.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtuszwekrz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtdzzbjiwd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gthoqoviou.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtahtmcfnu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtilmyucpr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtujpozcwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtidpacrpe.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtxdmwgnkq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtrwdkhmfq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtgkvfjdsi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtzeujksjd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtnhwpivzw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gttxotqina.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtkaogjcjr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtlhcgfkdg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gthkxoddob.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthsmeumjs.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtfeinzczd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtswilibqf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtccfqhvbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtzaajctew.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtwopyqugo.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtbcuufqnf.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtgwtmmppj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtprvgxjdg.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvczdhnaw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtbnoblgas.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtvsndxrza.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtlkpkwtcz.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuslmauev.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtmyymnchl.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvjircdc.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtccqaseve.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtgxeknhid.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtoqgbohcx.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtyrhxqcim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdapvjli.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtmhveccnd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtbbkszoeg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtlhxhruxg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfjzkcdj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtpaiofvek.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtxhmpqtya.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtjfxrixbm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdjwvizmi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gtiglabdkr.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtcysbjffb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtrgdfrjkb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtutdbmeuc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtdqljmqba.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtkaevdcek.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtqdukryyu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabfgorfj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnusulmjy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnvfgxxt.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtxrflgkxe.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtywmbadgk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtjfvmjxjs.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtjbrygoch.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtkihuwtct.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtsjijfimb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtkijjrzij.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtdmvrwrhf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtckxxyqna.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtlrctizyr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjjtsulw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtzomggtau.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtgixvklfn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtevoaqbhq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gtrsienbwr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtqemvasku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtbqqaxndw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtqcqiensr.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gttyxikcxa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtbgorlpvx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtaljrxdyr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtjeoixzxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtdfkzuemz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtkyfjbdrh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtvzdmdudl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtjjneihuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gthqitiaeo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtkvjfxbsj.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtetwhpkfm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtuusdmtrv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtfbotnrtq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtddkcetsa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtkqvhzfdr.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtrpyavvkd.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtujsdmvek.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtamtgpfyg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbbyhhnfv.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtfbgndokc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtukihctuu.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtmaohfumr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtdczrjurl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnrfsduq.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtvajcqcuu.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtsvbzxajw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtzxoansfa.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtgkcqysfs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtcdflogsk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtxnfhxejr.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebjpfbcn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtraybxdxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtdvjyiyfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtjsbsdhyw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtgkpgadvk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtkmtduovf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtrjtmzavn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhqwvoku.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtjdjzqumg.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtwkssqrld.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtboymbbdd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gthppiswyu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtsqipnsxr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtnxukkrup.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gteotfnyxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtujqrxadg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtnydkzoqj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtxatzdztj.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtecmasjxg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtqfjlgahb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtkxsidyje.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtdzxetpol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtnaqrelrr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtfaybmbfl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtlnipyvdm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gthobupjht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtdtubmvxt.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtqvibbokh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtnarjmgbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtzepebvvx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtwjzpauwy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtdxkdqiay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtbzkkcuvj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtdxjpfbrn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtpksfkgoa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtyknsyxvt.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtgbijfpxu.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyakvito.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtpcmhjrcc.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtnzfyayiu.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtpgxqlkft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtakfhsnns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtgzamfbjt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdofldxo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtcempewmw.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtaiglovvq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtyduduzdr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtzogfxoal.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtwlewcrfv.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtrogzrkoj.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtmrsfrmhb.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqvikklw.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtsqbtusch.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtswwfxfka.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtashaigii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gthzvhistb.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtlfrbyxli.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtmhspmrcc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtykubazwh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtsoplwbgn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtbruwhahy.html


<!-- 参考信息 -->