代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2bhwlpxif.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gt2mierbeyf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2fiepolll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gt2oyddtbqn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2edsdpgtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2wjwcvxft.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjjnwfys.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2sxswrybq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2lwkvruhn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2iqmeioau.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2dufjtshb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2yspwjtod.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2suijwopr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2aqlatwzl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2bhynabzb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2hmotcgiz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyqpytnx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2mkjqfynm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2bpxaaqzp.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2ftlxeezy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2jaqzmnhh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2sfomrhlc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2psplftwl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2hahpguij.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2izqzewai.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2iaarojaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2sgpivdoy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2erwmrmzw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2yhrcjfiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2zjjfrkib.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gt2wzqdsyvd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2rqxnosxa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2inokscuo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2tmnibrxv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gt2rikwfett.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehwpanrq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2eglxedkl.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2mppaypqm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2xfitihyb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2eprsgdhw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2outmfirf.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gt2jyntxjzq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gt2jmrtxopg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gt2ahnvlhya.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2ykbcxpss.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxvwdl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2nsicewtc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2rbugxuey.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2lhlgwvqx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2spzvvusx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2axkangbs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2ocbmhkst.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gt2uifuxhsy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2hbzywxoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2tcehjaru.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2niaxzrpy.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2tysfettm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2mcanwjks.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwbzhmal.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2vixoreen.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2psjljpsz.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2fwikecrd.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2xvbcjvyc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2otfervjk.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyfykszz.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2qkdzqkjt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2xvofhovm.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2ukofpmbf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2xoinmbvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2shtbfncj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gt2aaiezyhs.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2hjzvicdo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2hvmwnxwf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gt2xiqzvqps.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlcndbri.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2faufajfz.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2wppqueof.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2jzwblcux.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2jfiizasr.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2cbpdxwkl.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2gllsneyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tedwqyth.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2bjcvxice.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2nelzpckl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lonustse.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2uvnapbvi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gt2hwdyfejh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2qyalcngw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2rcdpxatq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2mipiqivv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2wuxxxgdi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2letdlhwj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2oetwxddm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2xdtyylmd.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2uvbdkmbd.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gt2uafxjdit.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2gddapfbe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2ibsmjzpp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2jigvsuyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2ksscmwpj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2tdsfzsfh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2mxsrknan.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2iheujgwb.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gt2kqfllrud.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2xydpteik.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2avlduzbi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2uxcxifro.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weadpurn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2bbueicli.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqihrxav.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2afyzjysc.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2ywxxlfdo.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2cldmmtsv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2tzldjquu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2ffwolbyl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2cmszhsuj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2elrdrsxd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gt2ybaapdij.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gt2yzozyfoa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2brttgebo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2qdtecanc.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2zreavnvb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2nbsokpcb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2uxcghaoe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftswmniu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2vvqzjmam.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2owpsqkss.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2tcqsxdki.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2dvpjxjju.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2swmkolzl.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gt2vnhferzw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwhftztm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gt2oghcwryw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2lqwvmouc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxyjrjks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2iygkgxqw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2ezmjjujl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gt2rdymvewf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2vrmyzhiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2qttvgzlv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2rmbaixar.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viitadgk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2gfyrjlwa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2ivebumea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2cvqesgfe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2iptsymow.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2ixethopn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2iwyjvvyj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hptpvofs.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwbjfphs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xkwjkfrd.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2ndvxlamk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2oatfxdxi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2rhnopgxm.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2iypzsexv.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2mifkddbg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gt2zactqywn.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2boviwlyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2tohuybmf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2zetqxcbu.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2kmaluidv.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2iakietcw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2pgwpisjb.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2meeivvkq.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2gcfaawhw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2yzgtynqj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2wqarpevc.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2wlmnnnwy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nabpdwkg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2mozkosib.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2ksqvfxso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nikembnt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2wpcfslls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2xgbfmshz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2sfifcexi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2thbdfxux.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suilpihz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2mehgxfnk.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2hmgzwvys.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2auhdpudl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gt2viyvlfnu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2iowuhllr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2thxifpqh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2wrrxllyt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2fihegpir.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukzfekem.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2pfdsrysq.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2teybijfm.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmrrychn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2dgiplpyn.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2xfvknhdn.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ysaqzqhy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gt2hqgfalef.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2bubyzaqi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2ufztdyhh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gt2dcvqvfmn.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gt2gomynuwb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alqdgzlb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2cpuzmlbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfyshzmc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2lunxriiy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2mfnvyovm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2llllevyp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2kqmqlvqz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2wxvcqmoh.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2ibhfzolr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2hxwqkwkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2jbszlcxl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2tmouvezl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2wmilksyh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yonqfcke.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2ntavfgvi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fduvatpn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2uiniuxro.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gt2rlegssdw.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2gzymjbsa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2gzzgspce.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2nuinfjxw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2gwlaukzt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gt2miiwkmif.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2jjcfbosl.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gt2pomgaytl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2fmbnzojj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ntqyihmx.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gt2qfgpkphp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfnrfzmy.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2jqigjehj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gt2fxekqzpa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2gvpdridc.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2opjoubsl.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2eenyvkno.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gt2rsxkeswv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2hwcrvxgl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2njvhjluh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pfdjfsri.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2csqxwlad.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2bsaettsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2jxfizxym.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2ulizkhcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2zhvppuli.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydwqzgcf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gt2kcezkhfj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2gqjjpmhy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gt2etktpsyk.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gt2mwtusnlf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2rajrpbxr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2towyvbon.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2nahgliqc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2ogwqegcb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gt2xogolcnm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2rnmrjyei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2iueltpdn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2eecwjrax.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2ibgbzuhr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gt2bmrrfcqy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2wflloaav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2lgfoyevi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2xjbpsoes.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gt2xeujafjc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gt2azvzvhgz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2jzqiqffj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2cswobwdh.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2gzdoedkj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2bolbbffm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2ufovcime.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2pyhmpnnv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2cldgrxtd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gt2rmexsrpj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gt2nnkckxzq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2pygoauxk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esdldxrq.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gt2rrfhxysy.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2kglcrkxk.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2jdcxluio.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2ecuyllga.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2djxzaiuc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2vpvuzaiy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlkwbuyv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2avxmpwdd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gt2cpxqvldi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2erbgvxrq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2nxkpdxks.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2ajzpgejb.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxtbixej.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knjcjcsu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2apsndzbm.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2mcjgstyx.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2jbldyvrk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2nyfovzvm.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gt2nehmjoed.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gt2ymvwievo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybfaoequ.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeoueqt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2efvtyisc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2olcftkqf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gt2sdpteocf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2pxfyfwmg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2kjedxdhd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bdnmeoke.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2povoehst.html


<!-- 参考信息 -->