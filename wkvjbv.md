代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ptdykegr.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2waivrhgk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gt2conhheut.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2vsjubwdx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2rhmfdqus.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gt2kakzglcr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2oticcejy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2kledhjyp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2poctbgbz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2utgnaqxk.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2wechgrdw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gt2bhwegktl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2bkugkllr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2kiouvire.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qupetgku.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2ixqjkaeb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2khqkpjjx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2hzbywcsb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2carevqcy.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2rmkgjiiq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2cgkiakmv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2zfdlsftw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2siqpmtee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2pdyuwgqx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2gmxprygl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2wzsrhqfe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2jtukyjgh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2kyihsmpb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2zxxzmqwo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmwrsnkh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2ijbtuhlu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2glwavvin.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2dpawzaji.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtqqnahk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2gxqzyewy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gt2uapmepzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2cbgwmhve.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gt2kbkbzroa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2lfrjedaf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2ognzrlgv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2tndccpsl.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2dknxtfbb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2evrykxay.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2npdbuffe.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2scombqqr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzbdfyys.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2urzwuvnm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2vkwiwvqs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbcmlcwk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2qkwsgwrs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2bqleotyg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2vsxgxvhs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2yovpowex.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxfdgmw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2hjycodya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbvfjel.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gt2ofvkqser.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xnnfgiuz.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2splvjbml.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2ijxvczke.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2eyzgnfjd.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2ktutaoah.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2ailesmzz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2wclhrxhs.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2kghmufrm.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gt2soworerx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2agrbyoko.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2dqprdfky.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywxoufxk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2yobuaqwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2urkpnxhy.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gt2kgjzqmiv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2tvmsfpcb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gt2tefjqmxm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2pjxkwwqj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2gaptuxja.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gt2uktbctgx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gt2cjzqpbki.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2cmmvikjh.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2lkoqzlzs.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxsjiljt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2yctzoyzp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nedmuerg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2tjzlvblu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2nybdmbfh.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2zayffmrx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2uwvegibv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gt2vehnqisc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2ohkyukcu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdxzattg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkgrrri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2tgilajnl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzhhyhxl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2szcksaqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2kixrmqwo.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2jninwqks.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gt2xfgfnuti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2bwfqnhoj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2zwxhwjlu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaiforrl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2tbqpvzob.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2mysanibj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2wgjfufkt.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idziwbrj.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2isosergc.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gt2qtkzrrkd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2qvajaqjq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2ybwkaobn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abrsqcwg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgaalvmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2fhrsnsls.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gt2ncmueckz.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gt2xljxfnmv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2oaomjubz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2hculxtll.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iylrttzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2awomdvqd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjatyqhs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gt2yavrbaui.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2ljcdmmgk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2sgsemhsj.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2miywjpko.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2llrpydoq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2kgksqylv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2vaebazok.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2jtogeppc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2whdjvwig.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2byrsnkyw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilyfoqzq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2letiwfcs.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2bsnsrhif.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2selydjgt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2nuzofsvh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2zodjbcks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2qccxvlih.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gt2tllqoqlt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2sfygfsvr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfwwrfrz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2tlkasfgi.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2lxvioebf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gt2ouccnlfk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjzjlsoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2mhcawded.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2wwsxegir.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unscivyw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2czrchews.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gt2qlqcakix.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2szbfwsbb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iwoclrgn.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2ckemjymo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2oxztxift.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gt2ppfjmrwg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2ridqfqzv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2yccvoqek.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2sjjgcdyq.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gucmaiec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gt2ogqiyfvq.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2bjqftryr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2shbuqcdh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zslnyxcj.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2nbltxnep.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2sqxutifr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gt2epnqoauc.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2ezyoheya.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2cxinljvd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gt2lnucfzqg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2kishjxoq.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2erbpajfq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zpijelrd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeyrqbdi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxugrxfp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2chfwgqgd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2gazxplpn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2fhdjlzqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gt2nilvmtwh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2hdingsid.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2qeqbptbv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2pespeabu.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2ejsbagls.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2zawoolav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfrxvyhi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2woyadbnt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2nfkdrdkg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2yrosjelt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2jluouxjn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2eypppbnf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2welvmltv.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gt2pbipyzjs.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2eewixtkj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2sxkewwqe.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ujxdmznx.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2apruonoc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gt2uhjauzzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2caytipqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2trhofdit.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2vysulrnc.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gt2cojdumxh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2aqvjptgg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uymeulsc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2jmboxuol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2abmfnvdj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2mduyhhnu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2ilmcefme.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2jftghwzg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cplvlyvg.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2uvmsnntz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2krjcobhv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.iojbl.cn/Article/details/gt2idkujmqw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2unaylgcu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2uxclzuyf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmajsq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gt2aquzikre.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2stxhraoh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2uztficai.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovjozsfa.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gt2bfgsogja.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlylphr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2ggrttznj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2vehummaj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gt2wbwpcdvx.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2ptiwgftv.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2rjrutbrw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2iqzivaic.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ebakvpmx.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2cjkukrtx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2anlheaqe.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2xultypka.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gt2urortqus.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gt2hekgqqcz.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2drophopc.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2hxwxdryn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2yyaqvaph.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2lnndwgly.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2yzkiobed.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhboxcyw.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2bvibhhqs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2pwpzdrdu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aslzrycu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2ftwqukmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2scvyjlsu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gt2lsnkvsae.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2rofmipvt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2amrsnvdu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2utpgwjhy.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2hxzxiblt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxovtjys.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gt2tfedowzv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxsmwiij.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2gugyuofd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2znjbtbrm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wifaihsa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruwayvne.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2wpwwnqqy.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gt2stwmwnsh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2aaatjrzk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2rhfwhfub.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gt2vdnmogwj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2gpmhzbvc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2axeprazi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2gdvhwmfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gt2rlvcbpbh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2kvyfykhf.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xduofzgo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2onstxynt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivxeksem.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csoczefw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pewdsdeb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmzpybsw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2joyeoari.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwcrygrg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2obrqkiku.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gt2xvwjkqtg.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2tzxteubv.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2lhcnwxrv.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2sbagbnrd.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2ezkwotqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2nwqgccfh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2neketvqi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2iumzurtj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gt2ptaxxjdg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2fupkugqn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gt2slcefmkh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gt2snzmhorz.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2jueaxtil.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2qgoyazws.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2mmpmjrds.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2jqdspngu.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gt2kyooxkdu.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2kufpagzc.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gt2vdkgwysj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2avkqebmz.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2nliiqteo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2epvdvqqy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2swcgqshq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2qicuwqvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2ddyfzrii.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwwawepy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2wsauakja.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pgdyteij.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2zbnnggjh.html


<!-- 参考信息 -->