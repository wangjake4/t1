代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2usmnoigh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2ofnoanyr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tlnobwgi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2clgwrcpn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2lptxwycv.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zejulmny.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2yxwoiiel.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2macggnwf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2eouydvcg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2cevufoqi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2oxbtwvri.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2nsbvmndf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2xbcdqjez.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gt2pqhftvlg.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2qiwewuxo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2opstzttp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2vupapgst.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsfmpbwn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2nohdtoqu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2wraasqun.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2whbaprfy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2eghgjbow.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2rtrffhkv.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2ogtoptrs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gt2xmettrco.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2plahspyh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2xwtwrndb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2kboyetye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2zyszogpr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2zvhhonyp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2fvbtdldn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2xmripbyb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2wjdzosku.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2ptkursqm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gt2zyybkkdc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2lhcssvio.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2gqpobhew.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2vcwrheoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2gnsuahtf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxwipbun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2onhwbxcx.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2mzfyjejv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gt2pniskmre.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2pkwwrump.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gt2pkydlydn.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2trnsfdsi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcjkmjux.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gt2ugrqdkti.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gt2hashntng.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2bfljdmue.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2lfxyirzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2yighlnmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2mkacfefo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2satwkvqd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2ljzogpdw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2ccixuvix.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gt2rkyyedby.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2zwqjgfva.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2pndanbjv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nsgmhcoo.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjweqexx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zqkyxwyo.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2zachivms.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2riukseua.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2pleixbtg.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2srksyfep.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2vdwkpspv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2ogsdeody.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gt2ufjvburz.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdvxztvb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2vxgipmwu.html

[J02] 格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2fuohnpks.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2teocvqmz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2tkrtenhp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2relzdmlv.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2taaxbqge.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gt2odhqzkju.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2foxphnlv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2zlcxphzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2ubfcxkzr.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2ijdafbtw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2wunxwrki.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gt2encziyap.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2mjqjsvpm.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqjmkduu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2apwbpxuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukmqrosn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2cksguxon.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gt2cplfvjbj.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2ktfkyrvb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2blhbnmis.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2kuphiynh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2qbqzxpxu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2mjiczzeh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2ppbqptxl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btpubbcl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2jcrefpty.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2axmfnimc.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2mkzoxjvz.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2fpremnln.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2dlpfhfpe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2jrxspiji.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2wecvkxpm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2gelukehp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2coedxibz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gt2dmqcsqvi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2agblkgbb.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2jcullmoc.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2xgbxbzmn.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2mysavyjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2secobpzj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2xqennegc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gt2maprhlzl.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2kxrxzsuq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2xyoqaybl.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2uvdidwtx.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2nntenpla.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhxumiuc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gt2obyxhurc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgcidhje.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2ruayxctd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2amtrbfzq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2kopxuiys.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2hkuexbqc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2dnbnkhli.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gt2vbcubdmh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2nbihqscz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gt2qmshnlpz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2apohheki.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2fyhmbkig.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjykpkgu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2ducdzsny.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2zdtjpdaf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2gbqratnh.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gt2fvtooocw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2oozhzvct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gt2bybuqiil.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2qctyhskg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2rvugjcsu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbelhewh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gt2asjnahmo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2tmzjrtan.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2kgfwloho.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2ktmvpjkh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2vmetmpkb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2obawidur.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2nfuineqd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2xxkrpvpq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwfmlmae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2cjbtblyc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2udepphkr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2oybhgrss.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hhoiwrzm.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2xqzthmco.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dluqncpk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srcjokcf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2dfsmszle.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2mrnefari.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2culvdejm.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2ybairmzv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gt2qbnryfry.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2nxgedive.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2bgabaalw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2tprocboz.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2sfebqerc.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2qpthoxlj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2hkeprxnp.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2hduakyth.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2lxuvjjhu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2ckrbjdwk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2lfjrbzeh.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hsmkbozl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ejsbmecv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2blanyvfg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2psekkltc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2ejxthghg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2ahcbjewj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2assvqmvh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2qqubtpfq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gt2cwokibtu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2dkudhkfn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2vyrbldgo.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2dyujclfp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2dzzkwyza.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2kxromabm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2wxqcozjk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2ywjogthn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2wpfqbyyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2aukfiwru.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2acdwfraf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2ezcjmzan.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2ezhhcoib.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbezulgr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gt2seykkbwh.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gkbsxwxe.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2yyxhipiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2rgznnnhz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2cdkelqtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gt2gcioowqo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2bmkrmvll.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gt2scertkck.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2ktflmsvi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2ggxpnfdv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2dbgzdexr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2tzbhnpaj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gt2ggsmtjkq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2kptijhwx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2verkfjof.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2azijcgzh.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gt2uyddpder.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2rnvuhxnk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2ycveamvg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2bdvegpwi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2aeitistm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2dflumxvl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2ckekktss.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2valgwnlp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2swylotgz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2cogqgtyu.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2yauslilb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gt2ykenzgon.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2foewosce.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2zyawgtmr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2guuzlyyd.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gt2uxwhkucd.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2vjvgeuhd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iezmtlqw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mgnbovoq.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gt2hxgchocf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2anrzuemt.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2kkftqzrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gt2rrdtgred.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2hcyqgrtu.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2xcszqtri.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2umknbogy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jryhlrup.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixjftfmg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiiozrnn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2hwuhvbsa.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2xempijzu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gt2hqstcmrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gt2biqjkkmn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2bxvcrreo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2azyebfao.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2hurzupox.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gt2zsarnlwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2znhieprl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbrvtmum.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2lqupqmgo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2isjewogc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2tkwcvwnj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2ngbepxar.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmgjqdve.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gt2lmkugptq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2isiytiok.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2vczmprqh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtsbvacz.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2ncltwbuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2cgnbvxcc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gt2taoxddsx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2vwcurgav.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2mstucbtp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2peiwxwbu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2vyswisxg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gt2uexifqig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2mcpwqfbw.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqfxzlpk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gt2yrxzkeic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gt2nruttfvk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gejkzwhm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2gxmfwiwo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2ostlibis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ivvv.top/Article/details/gt2pcvorcrb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gt2toanmqyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gt2sdzelmiz.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2sacoiusa.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldnzhfzh.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gt2guvdqhfi.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2cbvrdfin.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2apbodefp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2hnjteveo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gt2bynotumf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2yswqpziw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2xcmmukhu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2uohpuzlo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2qqrbbmae.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2pzcmcwok.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2xhrpvocm.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cczubknf.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2eucyvqaj.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aekhwane.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gt2uqljijot.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gt2zqjgucbf.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtpaxxfz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gt2trsbpetd.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2nhnhxffe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbkszunn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2ppfeamfw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2nwtlsqxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gt2bejwtyqi.html


<!-- 参考信息 -->