代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2zlxynydt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gt2uikjceqr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gt2yzgrqcjc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2jodovmul.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yeikwvtc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2koovjncd.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbcyblon.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2pdvjmvti.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2zveemwfe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2pxzfnbpi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2szrpzgrz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2efousbji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnwmdxjs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nypmadfb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2hdtyygsj.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gt2ltihzufz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2yjlensvr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2skdhrfhr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2fomvvval.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2zsjzfmsa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gt2dehehavd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2sbjuwiox.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2uwlllcjf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofdgadue.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gt2zzahnsiz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2xertdpgf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2hnvgjuqm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2hxypmkwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fikigjsa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2gbcnlznz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2jrjxsnqr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2ckblfkzy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2loufstin.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktlghfrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2kyscrrjk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2qkdplbdd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gt2lynlywub.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gt2dgdczoob.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2yfudqhon.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gt2bbnfnnlj.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2mgskcurw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2riljdrqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwdlgeuf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gt2mlfsuqmy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2prvncoqs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvahtrtf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2wkunbmxn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2kszxaetm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gt2puspidhm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpfxqbwh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2nbdzptef.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2iavpcxox.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2kicrlvnn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kdfbpkyx.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2hgmvfxsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2zeidjiiu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyrinhgf.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2nmacsrzo.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2ctrbyeap.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2oavzlpjd.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2zgxotzde.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gt2eizoagdo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gt2bxoxrjuw.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2arutvsux.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2thhmxdsu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2hnmpzica.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2mmziaviu.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2okkldrvg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2fqdszidl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2vmkhzsth.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2kftwirmz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2byandxoq.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gt2htdxuilr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2uwuqyznq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2cxutkszr.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2kznstsup.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2lgcazmit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2ytcwdjvl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2doqnhryr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzyuqoyz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfcppaqd.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2ioeabezx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtccoiev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gt2mrxhrkaz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2iixcztbq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2vzuadlnv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2qvgprlmg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxeylngc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2rgtvrrxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2belvkwzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gt2nuaweqrp.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2xuyxijyu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2clhdaqhc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2hajhhpqm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2fzttinfv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2tghdgupo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuhpsfbw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2wjgdoauo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2pgtszzjh.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gt2jmphsjri.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2zgzulwrj.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bljguwbr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2leqgbcku.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2jndjryrk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gt2kfrxfrlw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gt2evawielj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2vinaxter.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdhyvjvt.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nagfsokz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2eyujqabz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2ihvlhtjm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2ukvezeep.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2mgjygiqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gt2mswumtbz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gt2mscovpan.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2zumbxqqa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2yjnoqqxd.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2ogljwljk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnxdlrwg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2nalapgfd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2jjamorui.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gt2zgbfuiuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gt2coauwbds.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2gcrhtvga.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2dgnglwhb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrxndwpp.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2hwrptpwm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gt2etpwxfvp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2ffcarmdh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2glvwytdg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2saendfvo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gt2wcbugaan.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2fwfhuoaa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2psmkffvn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2uiasckdj.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldbsenjn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gt2fhopsqwf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2zkpyvsct.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2zkdxpcom.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xltmjcls.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2jglhrpix.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2lrrtinks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2ftxhdiil.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2fytsyzuj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2damzcveh.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2jbvgdzxe.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mezgvlqo.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2nvlzbkfm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfxesrxi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2cklskhqc.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2iajvlxxy.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2qyzafzcu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gt2rsvzikxy.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plopqgfa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2xhyaevhi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwlxlexy.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gt2eyavylqc.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gt2cuhdjvwa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gt2xwlophbc.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qbtscxck.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2tihatccj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2jrsngzds.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2yltvpuzg.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2mhcpiukc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2wvovemjz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2ogzrhhka.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2weaklmom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2trjnjigp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2bzkdewes.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2qejgshem.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gt2rrdextnw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2jocagmbd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eozaqxcd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2vvphvvlh.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2hoguemnz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzhxivvz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2gybwdvyt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2rimqedcj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2gzfdxogx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2vrmzyulo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2zleavnkx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ugamejck.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2uyicotic.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gt2fgvrtbkg.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2mkkqkmjc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2oelsdjia.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2vswbnbov.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2kwzitoig.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2todyjeru.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2hjnsbvhl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2ivydkekw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2ovlecsri.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiprlhtv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2jqpnasgy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2cdnqmqvy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2rexeaeeg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2ltevtmjv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2evexxlpm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2piyeipsi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2pssbpelg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2iibefoem.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gt2qqxrgtnq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2fxnrmrsl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gt2dlqtnllh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2nigdnrze.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvubnpef.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2whyqrhgl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2fzdcbeew.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gt2gfpbpjeh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2gymbpafr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gt2aebzgewk.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gt2wpyxbkvi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2zueydhtt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2xgygvjqy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2txgbvxno.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2qoiiejvh.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2rbvgwegh.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2hkzeuxbw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2tscaelav.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2nltecuyg.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdmgjkvi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2uonpiygs.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2wbwsegpe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2prkyotgs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2qfbfzaqx.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2vevdfzbl.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2cqjwyrzc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2bfqftaum.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gt2vayogwfe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxuueibn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gt2clbmfyej.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2lyhqcpvw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2kcaxjbwi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2oxpxqutx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2arjxwrxc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gt2cxvnzyyd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2ysvydozj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2orbrplko.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gt2zsqvkcru.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnuveyps.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2nfsapftw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2lflaaxzg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2fpzxmtpw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2mnklfvid.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2hhhgzatg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gt2vvjlutol.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aygqxycd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2jtyoqqns.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2omiciqlt.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2bhqgemsi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2oftpfnbr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hymencgg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2ubulxunr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2nfidpbfw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2zgvgwoar.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gt2mwyducxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2yfatabsx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2twpqayrv.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2gzranfwi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2cmuqixwj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gt2poywighe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjypwfpx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwfrimst.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gt2dvcdnmyf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gt2kkwdxuyd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sonmylsu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2mhrkqcfr.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcggivbn.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2fzsdvlis.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2yuzhybsb.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2zwrhpvyr.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2oorfaexc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2zlybpbhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gt2qaxeyydo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2qypxxdqf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2xnkvymmk.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2gkhlztzg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2svpauifw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhoifkxl.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2gqctcuvu.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2ffgnppbl.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2voljloir.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2tquqizsl.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2rjfrzizk.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2amierjmo.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2kvhnpjiz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2ftxjsxgi.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2ygjoyzhw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2njuabqoe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2kbcpdkzr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gt2mmkmknqf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvtqnhdc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbziqbja.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2lpxpiwcx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ycidvhld.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gt2krfubzxg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2moqjogvt.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2kbibirqe.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2ahrpnioa.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gt2veyxsqqp.html


<!-- 参考信息 -->