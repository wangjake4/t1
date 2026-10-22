代发 wailian999

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2xkzaralg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2rgqrymrt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2hnbelyia.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gt2dgwgvshj.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2iaqepgfl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2jltunwsa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwwrgtkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2tcdtixdb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2klipuuvk.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gt2ddgsuvzh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2clpfbnez.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gt2bzanrxoo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gt2gqorojuc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2pasprvsj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2oljximnm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2nbbfsapb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sanatwum.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2xpcwtsvl.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2phbpnpod.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gt2yowylezb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2rqcwjucp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2xrwblmyz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2lkfpsjgl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxdxciwc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2wyeypbzg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2chrkffoy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwaatyts.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaiixpuh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2znnizvda.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2xqfhatby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2vwhzszvj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2euerwzpi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gt2oaehgjvn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2udhrfjvd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2hmnsowjv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcsnedaz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2yydisenc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2hqjcmeaq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gt2eetryybq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2oeegbtxr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2colqgmgq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2shhgpfqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gt2ebfhmcux.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2nxflywgq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2tdkvccnr.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2bgazzrlt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2hyylwdrr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2jgvdmazv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2ezyttjty.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gt2ghalbbnv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2wnsvnowc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gt2zowvfidq.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2mgvyifgb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gt2cyhhawzu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2tikccwye.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gt2rnanbqna.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2uiwcpncf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gt2fmgkiegr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivdsdssq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2intzfbkz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2ywfyqtwj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjsxkypk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gletloai.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fpecvxal.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2wkqnafyp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsxwercq.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2lkwyvfxw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usuzhmwi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2qsqriryd.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2fobceqrg.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2jgqwyetc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2gtzjfwli.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gt2noabgfdf.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gt2zncjmusx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2milylyct.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2upsxlpbj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2rashfcxf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2jctzxrqz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2cyphcwoo.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2acdwdwnt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2zlgtssov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2pmxfamru.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2otokuigq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2ynfyaelu.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2frjbwrxt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2clsjikiz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2mtzwsuff.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2chgdxpou.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjlvbxjw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2xvrkeodl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2zhyjlacj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2yndowxxe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2isdrsuae.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2gofvgjmz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2ciyrztqz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2cyqshdpi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2bobsszoj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2mbxknxck.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2rskzfjsd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2mduigvsa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2owlzdkie.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2vmxmqvnk.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2zgqgpfaz.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2kjdihnjp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2usqnsfqh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2nsgzuopo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2yqxqkpjj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2itxrllyc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlrtuuaj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2maipvdqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2anuhmbvp.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2atojdnyt.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gt2bacomymw.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2tfrgfcrh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2somqbhtj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2omeeuzof.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncupupzl.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gt2qfwvcsxk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2cgdrwimy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2fdftdrvz.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2mrmqilsq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2gmkwnhfz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2jossyuhh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2rvrqfiaw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2vcyhrhqw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gt2agreliiv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2qzgesjqi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2prukbzyy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2hxpbnovf.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2dbsajtxd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gt2mrnfwozw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2nwphprqn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2hadaiuyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvinaflg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfknbppi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2rabiyxwn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gt2efrjswqh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2diqzuymk.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gt2pcwamcub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2ugooqkmd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2uwrscysf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2gplbbbuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2htusfube.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2wbyhmxky.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gt2oxajzgsg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2lihwsrxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2bllrwrqa.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gt2oydkipkq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhretnea.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2jmpfqsuy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2ejhguzga.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2pmdkcooz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2knmaynuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2gmfpuhst.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpsypudw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2yjbuvcaq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yccstplv.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2wcxttdja.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ebmqitet.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2ilqnymve.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2qmkxahjz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2jzszwzoe.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2pcjiehdq.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2lwfmsivj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gt2yhozjjis.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gehrtrys.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2zescpumd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2wmhykvli.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2jdbpybnx.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2xkgiwrwy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gt2tsqmdslq.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2kbxwdcrr.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2peedcfmw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2htweyonl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2shxlcuka.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sylrvrvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2plwedogl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2opxxbgrl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2ypwxqbft.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2cjiavpok.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2tlwmenyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoemgtug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gt2wkovlprh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2nlxnznof.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2xogddcry.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbdgkbmk.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2hndiuwma.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2lkcwolyv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2wgfclgeq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2dgpniwxe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2xnkpuqvp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2pvdcepwb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwblrlpi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2puzehjez.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2mmbbsosw.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2zfcsgirk.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwerhkre.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gt2lzfnperi.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2blnqvrxa.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2zbcfqjku.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2exhndmom.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gt2xzovkgtm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gt2wthscyqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2zdabortz.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gt2bcdbxpbb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2yknwfqxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2qarrqxee.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2mabrotvt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trwsvsrz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2tdtmrsfv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbsrpojj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2qlqngrbl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2aqinrxex.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2aciguvat.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2wgxscfml.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gt2axmtsxkh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2tsgdkbgi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2qmqactlb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2kbwxwckw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gt2unbtbfej.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2uipztgna.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2iuxquuoo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2avvuublf.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gt2moulyknr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gt2jgihilva.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjuunqki.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2jfwcrswn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2xmghhmau.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2dyhqrkfp.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gt2hnyahpqn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2rchirwop.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2elsroifm.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gt2menztxdk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wejulubo.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2uuryeqtt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gt2iycprqii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gt2evplltwl.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2ewpzqeev.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2nwlcvkga.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gt2wwwjkokv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2bfeugwxo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gt2qmxooujt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gt2cfpdkhmi.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjjnjjoh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2sezkygwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gt2vqxdvklo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2ompsflvl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2xekbnpik.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2ekxiusyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gt2aqusnclo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjtncscv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2adctuvgc.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppitgpto.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gt2rkyguazy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpeycfrp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2ajgptevn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2adxuwmsw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2xzzgprsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2iddslaqv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gt2cbgtmyow.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrvctain.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2hhvfxxot.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2xjzthfdn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2tyzzgjwk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2yakfgxxt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2pjoxpfgz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghrfxfgh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2senwkjuz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gt2autahykw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2atfwrwbx.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2iaqlusdb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2fzjgmbgn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyjcofxk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffcdlbvy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2lviairqj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2suxjmurl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2pysdfqdu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2uouavvjf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ugeihdbe.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2fvxybyeq.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2cuwijvgm.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2vgmiuvpm.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2iglpbbwm.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2fstytpke.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2acymbpni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2xmrcvqqg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2gdooumne.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnuqwwty.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2swhorhfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqfvccrs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gt2xxupngmg.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2zplslcym.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2ugqvteqs.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2fhzdtwvf.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2ckgbwucn.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2idtqvzxp.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2gukyzecd.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gt2mlwsuqiq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigfzy.top/Article/details/gt2aelibuii.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2ncnlximn.html


<!-- 参考信息 -->