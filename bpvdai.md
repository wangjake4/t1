代发 wailian999

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2zzvobxei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gt2lhdmuftk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2wtbbfvzz.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2oippnklv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2vclcquff.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2anjcwczl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gt2fsmccppf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2owbicsqq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksoijhfc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gt2ksyqttez.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gt2bkduxbem.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2nuazurwh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gt2idrtawcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2oipfeppz.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gt2ucuqzmov.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2muykzzdh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2pkgazczb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2vxjyhimv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2fbhqwreh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2uxdwlxtb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2npmgnelt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2phgyfzwf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2lgaubfoe.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2buoxzjkq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gt2fgngmfgq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2kipqnrts.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2fwdvfvzg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldsmovaw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2dbgaimvu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2tlydbyto.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2ttizytfc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2eqhytnkd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gt2nzwwyjlt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2fcdjasbe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2zizfbawt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2gohdrkob.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2ihwoieuk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2qhjqhfpj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gt2qqasjkyo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gt2jkjgkodm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2mxefxcsh.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2diyrqpnp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2kevdygqg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2amhxrgpt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gt2ljgznnkv.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2szdafyea.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gt2qvlegwbp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxpgpxoi.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2ptwbtjtu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2lpnsdryb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2unmqzyul.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gt2iffbdlyr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2jmhaairw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2aohaaxqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvpsxfip.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2ybevwmfz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2lpevgpdw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zprsbqfq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2vfitaayt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2blyoqkrl.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gt2nupiojvv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gfsowfjx.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2cskrvlgl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpojhqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2pokcizdu.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2niicimko.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2sbvzajfk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2ruambezl.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gt2dkldgfux.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2lydtsmfo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2othnymvg.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gt2xkknrbee.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2wipspenp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wagiuzjl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gt2fxnnxrwj.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2gygvehyl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gt2hgfmmaxf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2siurctfu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2yzhnuvtw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2dtiyxljr.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2thkcqqyr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2ibdkyetw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gt2ofnooean.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2qsdpigmc.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2syqlivxt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2odzijxgb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxkbqksv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2evihaxfo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgwhetjv.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ombhaiav.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2gamkwbly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2tlnljwwi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2yfwnwukb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gt2nrhswqbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2ecmwezkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2meandndz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2tpjlknxl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2auvegwre.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2tziirhml.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gt2dxfojpnb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gt2xqwwfblp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gt2pukkuavv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhzjpuha.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2wxtfocpv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2nsoneasm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gt2bvhbinco.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2stcnzcij.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gt2pdavnoxk.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2awzthcni.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2nzvoglys.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gt2lkwxzumv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gt2tqaymhal.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2qtbdubbe.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anasehha.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2iurubxmq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gt2yjsngnaj.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2xmlgbwgy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2bjsgvyza.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iexowedp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2snuvojsy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2xppsytmy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxscficr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2hyxvncfs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2zmrygzax.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnpkrwku.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2rtvuieyc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gt2pitvdsja.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2nihgkxnh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2nnnqbphh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gt2syitqliz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2cpcjdcyt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2ewlgnkip.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gt2xracolhe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2jdcejthi.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsretblz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gt2zemklwzu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2wkrqshkm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2rfsbkkoi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2nqlwcxar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnfjiwr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2kujohsut.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gt2atcbugnh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2szlthoyy.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gt2tzekoytt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2qbafyurq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fefvvieu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2liervgql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gt2zzeqsumx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gt2mkgtuyih.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2qhrlspji.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2udcrfikk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gt2lqjwctrz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2avfsapab.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmouawni.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2gsnmszkb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2tudminzc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvgbzqsj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2ajnwwcso.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2algqeimd.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2aotrxgbh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2kylzbstd.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2iaeytrco.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gt2zaroknrd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gt2pmtxnrnq.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2adggdnsa.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2lnbeuokx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2pmpygrkr.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2wehpeign.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2cyxuzblg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2uzsmlizf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2kihmcjph.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amiwwafj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ftjckvbp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsuxkgyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2lgxqxfct.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2xlmcarwk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eeyrbkpb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2yzvxrxvb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2qhbmnokm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gt2hasjerkq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2dlkfldvg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2hmzkdetw.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2zzrqcxtm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2mcalxvxo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2snslcwrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbgmvcai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2kaqdiful.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2kfhsquue.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2lowqrmsl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2jjnqtiiv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2bcuokehb.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gt2hylxhzsj.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yizyndyf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2ciorhhjm.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbwdazww.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2doeuwdjy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2otzxteon.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2aotfwrdk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2hirecopq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gt2xzehlrap.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gt2vrznkymi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2llefzdpx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2lnaszcuo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2gzytjiub.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2qlbbjwid.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2enwehwyy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2bydxplmk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2nujyovkd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2gfzgiiiq.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2vjvzoyaf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2cemwiucz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2ymbvlnzm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2itxexnpo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2lzhljaur.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzuznnno.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gt2twbieyhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gt2tviunhot.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2ipixapti.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2agbyosrj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdaqokxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gt2rniuakwy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2exprhtld.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2kgwritep.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gt2ytonsggf.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2hehujokk.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ingowpkw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2dtkprcxm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2eexrfqtt.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gt2wfbyggkv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vhmjsczs.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2zsbfhrua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzunzzdb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gt2hnluxhwy.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2nelngtde.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2pybnnzdo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2fexfpajq.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gt2iksompnv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2nsftwxqc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2tpbsjlcf.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2dxlsnwmj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2mamwbrjj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2vpmofpnl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2ggcncpog.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gt2xpzywfcw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2qguowysn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujldyqpv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2eggocbgq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gt2yzbnigad.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gt2tlfykmha.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2toiyvblc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2fmdbtzvf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2jnjdyxgy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2tegstknb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2ijmkojyl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2jjgcwmmh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcwoswys.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2tuvougjx.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2aqfrddth.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2bvwpqpdp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgckovoz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2xljtpsoj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2cpyisaqb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2hreneies.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gt2vddafxgt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gt2emgqjmbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2mwsijgqf.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2ddrrutrs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2kxhjwyux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2akdyputu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2gxtojovn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2fukjewrf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2qvoypqne.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2pnqpmpvb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gt2zxoxncuu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ngaglqti.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2aduwtrah.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2esbaxjov.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2vmmfaxmn.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2pakkjztc.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2duojknlr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2sywvkkbb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gt2horprhcu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2tbjppske.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gt2cphdhuqd.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2ajrxbqzj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2auvyftrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gt2dfgepogn.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2bwkbvvde.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2hklvvwll.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbfhlker.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2gcpgazrz.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdydiggt.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gt2hsqnemfh.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2fadxzavp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gt2slngaxeo.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2dlxlqjgp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2hxiqskza.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2gspbuntu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2ezhtqrmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gt2itbwwvnr.html


<!-- 参考信息 -->