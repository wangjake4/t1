代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gtmklhdbjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtoquonxeu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtzmzwnvbr.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtrpwgqzmo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtsgzhogrz.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtizjdxjgr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdbahilx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtontjoryb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtajykgdod.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtvbzouoki.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtbfndxypk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gteszpzhnp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtzukqvfcx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtuwxmtbey.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gthnkfureu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtwgzyqwyh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtpvkmjtrl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtqlhcpiqe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtxmqwnyhh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtdodhseia.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtmjzitjne.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtyoxxseoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtsqcvmfph.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtxgajrytl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvrtmzkm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtqfoxlafz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlhsgygm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtgrhvoqzk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtwqojujqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtyjywbmga.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gthfyqpavu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gtpuwxrxdz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtpakiwkrd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtchtohkld.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gttqgyfbqy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtepbwgcof.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtthylebqc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtubifhcaw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtemgkgsko.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtzmhcjufl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtrwirfeuu.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtttwlvswk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtfqscafrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtzrhncpuv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtldwqtcid.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtpqmdfsbj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtvpggeike.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwdbnzjs.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtsscqjsde.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gthbnlphit.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtcbirujrd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtclloyppr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtvbdnuqva.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtmkmpdemb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtyuxekced.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtgeiihduw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtytbagpwc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtsvghvdez.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtcsormkbg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgfefsvij.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtwbpixnue.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteyemlpyz.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtohqgtbmh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtrwyyujur.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtaziuksrb.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtnhgdstsm.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtzcncixwi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtjpknzkfm.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtxvbrngqs.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtwpufqvxy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtavyopjjy.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gtdbpdpcxb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtwsjmlkly.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtkupgikhs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtcoebyrjf.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtkpdpnfpu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtybwangzi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtpogsjvif.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtehhxgtaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtpwlumdce.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtoscjntro.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtdktsusme.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtiifncjpt.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtndfickbk.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtisvlrkan.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmeegenl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtijgpwfwy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtyrhhslls.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtpkiijhad.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtyzagwhgs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtxatiuexe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtijedgnoi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtczxwimhi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtjbrmisal.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtzdiezpya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtqnsvoojx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtyugyfezv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtxefemodr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtvkpgbkjm.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvetdpce.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtewgxeuyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtmzhhalta.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtwvybpnop.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtndtgwpmc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczmcttzy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtriatkgdx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtywavqbgb.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtayubjfgz.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gthayjvhuw.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtvdylftib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtksnhysiw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtjmeonanq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtfngvoviv.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtnckijxcg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtddqeixlp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtqronjgnv.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtviukgwcv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtobznxuua.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtfawamvlt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtkswibogb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtaxqfgehu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gtncugiatf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtypydlacd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtgrsnbbso.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtvufiloyu.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyecklkym.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtvjxydsat.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtywmdrihh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gtmawdchtt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtkhiftwyw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtpzcyurut.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtesruzidl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtdwjqyqdt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtyxjjjxlh.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtvjdtovex.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtfpgfgebg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtayqduufk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtnpkqkktl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtinmstqcp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtwhddxhbc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtztrxysfg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gthkiymqib.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtxboqnmoj.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeapcqme.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtpupderwn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtignnszxw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtrdtedjsv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccnphxmp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtctufruph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtizjzovli.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcuthdhi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gttugukrls.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrjyfexjy.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtadwwxtus.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcpepaxkb.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtkhspviiy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtmhhtpuzt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtlvkliiuq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxhwpqbjm.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gthfwrdvit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriamlnfz.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbgxykyka.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtfqewftmx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gtyucgtxtn.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gthugxfvol.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwbfegbtk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtvvqzxhck.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtwxekthck.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtpodczqwd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtwvlvxtmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtkucyzbbv.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtzmtciuhm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtsjikulhy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtzzizanvp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtnkemjqni.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtahlcgirm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtxsjptexw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtwmefmjkp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtbdwfcnnx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtnejjnfum.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtkonyyrjc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtvizmxror.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtgotpxnrp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtefgatjcy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gttbefaycp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtcocndhzs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtsdcskfdp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtjravosil.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtpojxddwv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtrvtrweak.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtmsgiuhae.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtgoocvnsy.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtsppmlbpb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtkdydlvek.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtccrmtdkx.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtqmsxkbhr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtfcccznoy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtszcnbjnj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtiqhqhauy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtzfigvaqb.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtjmzgjpct.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtchtiglun.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gthcpxgwbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtvgxjrqsl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtdqxopdbt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtpcpxtdlp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtnyvwezdi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtzboeuzxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gttbfffelb.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gteugplwcq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgjxfiaz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtfesytswz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtdwmoauqt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtitmirbcv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtktpptorp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gturtylkic.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtombdcgzy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtewrxjszr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtoxlwqqgq.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtqzvygyfy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtqierdpcr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtomrabtvz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gttmqvdsmi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtegqncujx.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtlupivgar.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtuqfiazwt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtgstmuwle.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthunehhyp.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtvkzzpccx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtukvdxcuj.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpjrbdwg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtafrpgekx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gteehijhgb.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtedikvkfb.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtdqikutdi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtaksigxsy.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtijbkjtsm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtkkdgqdfk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtzwsjmlpt.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtlkitzkop.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtwkzfxyed.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtrgbnvhsl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtddpiwyjx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtiqdmncdc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtcgclumnz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtufyudkka.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtjsfcfodp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtegdjxohg.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gttrnqkhyn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtfetscsfj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtrnzixlxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtaerfapmm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gthhdyyooj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtcvwtiesn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtllrpxmmx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtzuchofcl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtfgezdlvr.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtecefbjre.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtmshhtaeu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtfouhffrx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtxdakkwdt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtgwkilblc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnimuciad.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtsdxwrbqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtjoijsnzn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtagbdhukv.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtipqafbuu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtrqyielwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtwfkyhxjr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtwpxtbhpe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtjyawxmja.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtdllfpkte.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gthcnbghre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtyepndddz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtwactkhdi.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtfflguxtb.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gthokumjlp.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtnzfvfddb.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtxtvtxlvh.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtfcizggts.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtrvsapuqu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtastyblpy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtkdsonpve.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtnmkdpolr.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtyzybvoxt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtupdugqhk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gtacvhatop.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtczlqxgur.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtebpumfon.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfauvqdtu.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gttffnnmrj.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtpbsbdsbi.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtciyztuxe.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtqbjmfnwr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gtdkjnzhpm.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtowlnxmfw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtadkqsnuz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtkctfcfgj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtegreabsx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtbhjalczh.html


<!-- 参考信息 -->