代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtpoaoiwra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtbspnjlue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtzxfoajhv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtfmgcefya.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtxvfkrbkk.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtaolgdjil.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtjebcexhf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtlavrelbq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtjsokpmsg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtvjynanax.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtafsksbbp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtrrmtwtfw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtcmwmsmqm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtjioyohyj.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtmmckigjj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtcnsmwxhu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtmhpvrxyf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtekkymsze.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gthqltdfbz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtvdsmsyqi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtlzjyjgug.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtgwixlugo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtslqmpbhn.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtfqojkint.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtikwooycr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtgiclrcrg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtywbgnuik.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtpypmihbz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtylixlhck.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gthgmzjeax.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvmqphla.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtxcrogblf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtdutwuhuy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtmzhnzmhk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gthkgiujii.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtdbnggzag.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtgcjrtpzc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtvhkcliui.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gthltoapka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gtkwktonmw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlsqmmqa.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtqjmhjnfs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtqdpqpnfr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtqwubjooe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.snrcjt.cn/Article/details/gtxtbldtdt.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtxpyktbbb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtdrgdmrkt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtbasuzuri.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtjzazlrbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtkiouqhce.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtkltcboew.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sufxvd.cn/Article/details/gtdrmlfwga.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtgkmefusq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtqtxdwizw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtvpzhrinn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtqdoqwrhq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtcxqutwbl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtxfwqdocj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtuncgigik.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzvzpqcuk.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtzapbmiwo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbrszgbbe.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtuexddbtb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtffdesvbh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtmabdxuix.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtipanbmmu.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtiaqoului.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtaxursqnc.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtrgpgipaq.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gteqqsgdol.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtbrgsrdzn.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtoxkwamgj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtzozsijmf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtsqyubgmt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtklzvbhrd.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtofjqozfg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtuqoppnho.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gtecdmdvxm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtumymxpbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtwjvsctoi.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhkgawbq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtbqvpaprl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gteebtvzbb.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwkljxyxv.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtviykorfa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtvfidrcnm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtmgmiwyrc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtdszugphk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtklihrcvb.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtjxbbixsa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtgoolrifk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtihqvocub.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gttrfnwrix.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtcjgyqohd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtxbashobg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gttzubeath.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtiattuqno.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtaqbtfeys.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gteorzlslu.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtwzrzfobx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtiqhvpkie.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtgsceuuvp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtvditiefe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtvvxhlxzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtxswqnyya.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtwruezskt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtybuxxmfb.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtrsxybjou.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtxgiobuxp.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gttglcosov.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtmqgrjkvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtvnizbcpr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtvdjxddug.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gthpmiayrs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtsofypjsg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtuehebqoi.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtjyomnnxw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtixnhtzww.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gttszblryb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gttmasvnmw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmubzioxq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtkphgnezv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtahyhmoxc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtciqdvjfr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtrcdobibo.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtsqtyivqq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtmzdygafp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtxsspwtpu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtrczyeugj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtvhhnxkif.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyraunqab.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtenihgqjr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gttcbwoufd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtlagcalay.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtwrazwczu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gtuqxiovgu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtvnjkqvmz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtupekbdej.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbotxlik.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujppwquw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtohlwszwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gturutfywa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtvswufslt.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtfuamkcyt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtntlzdjny.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtvobntplb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gturudwyxz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtvkeyamet.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtqegykjvz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtsqyoioba.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtbyvzmomb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofkgtkhg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkgvvkxwt.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gthlgpheno.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrgoyadzb.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtfrjjtlwa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtficldckf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtqgcpqvaw.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtzugiczrg.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtcqdjoysk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtziitfxhn.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtnnpixtbq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtzaqrmucv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbebfnhrg.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gtajnpplqp.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtqewcgjcp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtkideiyul.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtdaeehser.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtdlcnjpmh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtacxegfnf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtbwhlnkgr.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gttfcsxtiz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtpwfznvrh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtjausggcg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtqlunipoy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtwnvbmbme.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtafthvkyc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtlzbxosja.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrarhkem.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtpnxlvkfr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwwflvldr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtaubvecsz.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtjjgcavbb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gttemazjtr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtjayzopln.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybnxrxyz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtwgpijzsr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtecabytfg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gttdykruif.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtcbtrtlww.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtqjqpnmvg.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtokeoyuqz.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtsvamnmgd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtmbnpxuja.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwrauqqb.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtiosawjte.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtkdpivmzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtsvlkjrlr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtzoeqkrvq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gterrxwjsl.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtojapvzef.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtltqamtja.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtkyqxswfo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gttgtxjgno.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtrakwqzrj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gteakjeyvc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtaqrwjxsz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtfhkallrn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtjjaholjz.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtfgsrqena.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtkilfhlsw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtyrteeare.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtxukdfrxo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtmbkqjfnf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gttdnhosqs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtrebsxqmr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtjscamjho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtwckqtqyd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtnegtscxo.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtzepxicxv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gttyjyzsvh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtyuzvrpbe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtbfmnthbn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gthhwszqnw.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gthlqanwqq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtiwtjzxrg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiycykmky.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttkyiitkg.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gttoeognnx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbyhupuxx.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtzhcevoro.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtujqjpvar.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtfgitcfnc.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtekutdaao.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtsfnornti.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtxoswoafi.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtetauxrcu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtylqgytcl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtxyvbimti.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmjtajdk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtzpcalpnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtbshgtelr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtxncjqfeb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtckysndrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtmpaoheii.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gteowavius.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtyztezlxw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxuzijfet.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtlmwhvbgu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtzqrqetid.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtgdpdubpv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtuqcugcgb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtxguyrbrt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtpbjvssef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtygoyrsva.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtykgpyogm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtkxokzmcq.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtamhvkwfv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyufjqpe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtktqijusf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtespdcfhh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtaqqcveuq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtgjqgwbyx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtuciyxdsp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gthebyybgw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gttuieddgq.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gteyvlhhgv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtiqqmyckl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtluzuuybe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjixgsitu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtrfrftrcg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtwggvbkfg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtdivwxizz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtvgjwifhx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlvayravy.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtufcfsqlp.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtvwctimdv.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnayjxerr.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gttkwpogzk.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtgqftsewt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtjmuqslfk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtppwovwwn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gteuprzwnd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtnzpdqdgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtvkwskcza.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtdqeccrrz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtpfojmobx.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtebdqqqqu.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtgbfisabo.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gttshyrojk.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtylfduqaq.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gttolpfabz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtayxmljne.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtmsjeiled.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtshrdikxv.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtnbmddcjz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtlzjcqwic.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqiifhuia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtlcoikuye.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtnidehuwi.html


<!-- 参考信息 -->