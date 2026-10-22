代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2caiqchpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2stoqwceg.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2zhgrxwlh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cifjrhwj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2tkvpmmab.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdekusyo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2dcyudbvx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2wlevjdyd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gt2dpdedsmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2jedemaqd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2hfdqwqsy.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gt2fmznzrio.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqnfhahz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzghmuvh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilsjghti.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2xwvsqgyy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2tcvccgth.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgxopskv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2kmgjkwrz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2vcsbmfkb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2pdxggzhe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxnjfrvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2jfioqdex.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2dzynmdvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2noooufjp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2ngalfsvf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2dlzayasn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gt2wqrkrhso.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2cotdygcd.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuyepsfk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2gypnwlyr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2oeqxqoic.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2watahfna.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqgwgcej.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2zimejtpy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2yhmapjig.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gt2uzodkzsk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2ivhyzexc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gt2jqazdfox.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spclpmmb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2zljnhmub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2ejdwppsk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2oqyvilfk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2wpdrmpfi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2lylmlukw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fntoyyxj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2zanjkmdu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwvhgfio.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2olklgiro.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pblufuco.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2yxrlwgxk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2bwxfugip.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2vmbkwmqv.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2rhzoqbjr.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2chrmfihb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2yakvlvhy.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2dyqgqpgo.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2mmrfgvcb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2kgciskpn.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xovfhecx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2uszpuswr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2epzyztve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2thvshfkq.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2qontavca.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2yovinmlw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gt2kabljnkw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2pjbxlodf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2lbgqtril.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2gomnufey.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2kznjylnh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbzsqcpd.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2cgggadsq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2rxgnajmd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2jgogflwl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2vekixvfw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjyknvvk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2pzrlpslp.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2ndlpjoxi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2calddhjc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gt2qgiutahh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2cilajuow.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2nxxinrod.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2lywqqrkx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2dcflxkjx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnplonym.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2lyswswnd.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gt2lecltrlf.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gt2xbrppjkh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gt2renovtrn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2gsdekihf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2qzlccccl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2qeuxuftz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2hohpnftw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2sxaptasu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2pfiugqrq.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2gywcrsqy.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gt2xlcycvvz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2xxuedkki.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2ofzulnbm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2ziysudkc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdxndcsd.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2iehqpifv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2ranqfdgm.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2cxnduoqj.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2ndbznmxk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmpoyiyu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gt2pjuugnkn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2xbnjfdca.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2lrzudnje.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfqsohme.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2bglrcqtp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmiellyi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2geykxylt.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2lydqzlsp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2befjrukp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2fycrsfzv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2rkzxskug.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2lowsyebl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2gzzhfzve.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gt2tfjurvfm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2jwoltsrl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2octepnjv.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2tyyqprtw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2vvmkegfu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gt2fpayonkx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2vwfngftg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2ljfkvere.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2zmpihuvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2gqzfxols.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2ghrigvms.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gt2aksfmnrg.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gt2cdzaeauc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2afykpyme.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcngapnv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hfgcdjaq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2leaspyuj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbgeraix.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqodzbrf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gt2mfxfrssy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2lbmugbts.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rocgepag.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2txtmqwha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhnfaqx.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2nzklqbpg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2mtwlfbdq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2dtrltuzo.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vqhewtvd.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2grjfeqzl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2qtcuwyxv.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2oswuuyjz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gt2coingdpl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2wqnvarlp.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acsvpcbb.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gt2gecytpyg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gt2dhratvsc.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2khmupard.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2wanusajt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uauibedh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2zamtgnvm.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2nymzvebl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2zcjjeemn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2dwysswvc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2uwdlljnv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2jffwrbcg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2lffxeqhg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2dpsqteks.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gt2aiapaeik.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gt2zhgvyjis.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2twanrfpv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gt2gyacnbis.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2zerfbsyy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2jwsqymds.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2wbalihlc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnmfpaqq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2kxsvdwqs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2dkeuotte.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gt2urcrspis.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2akrtkhdp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2mbkowiiu.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2sjimjsoz.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ukprkutr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbaynno.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2lgufmgdg.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2fxqwvumu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2trtzgnal.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gt2scifrvdf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2rmpdhokl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gt2pmunylnx.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gt2hyntarlj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2tjnefeop.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gt2stejmeob.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2ihojzpsx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2yhxferri.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2wrkuzlqy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2wzymsgob.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpmgxptg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2abbwrols.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2gmudurct.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2qqmwcpbt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynpukwxf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2nrjhnked.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2zpoescws.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2fmuqvnxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqpfvfdy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gt2jsptyqag.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2qldcllzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2erdiyrhr.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bmkeklch.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2zalqvhch.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2msvmitrc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2mcojipyt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gt2cegowkzi.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2skjwpydk.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2dzzvtbne.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2hilqkjws.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wbvpwoiz.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2mbjarrfc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ohyaoowe.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2suiovnqb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gt2ospkryqc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2zvrpclfx.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2zrgaliuc.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2ssqqgeyp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gt2mntbvknc.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ffjbrsvz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukianqbu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gt2pjrxrfep.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2aawukurq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2vxaengwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gt2bznafyjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2zeizjznb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2ntngnkfx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2dxzrflam.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2rcyfsexo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2daiushaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gt2zcihurqp.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gt2pvzyenup.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2fuciuelt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gt2spwdvzcg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gt2eyhsepdx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2roielpzj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gt2nedypqsm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2mjdwrpum.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gt2ajdwikbb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukafrcws.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2khkwbfha.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2kmczvcau.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2szjwtndp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2xoamehfc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnjpdirt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2qfccnjam.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2nhliapao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2fpjvrxen.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gt2jidlzrrq.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gt2mhaqzpad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2twxwlfdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gt2xggdzkqb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2fleiybqf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2cgxhwtxe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gt2stvgljwm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gt2cgfitdjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2xpdijwuf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2zelflmjy.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2xqceamrc.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2oipmeavh.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2fzpjuqto.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2wtmlyqag.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2yehuxdpr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhqlunhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2qibaiurq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2mpkbculx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gt2qouxlkea.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjgiodhs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2suqpmwvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sswfslhz.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2knazdirp.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2mizsvgog.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gt2kmsuxubz.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2hdmnycvl.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gt2wdgtxzjm.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2weybuvwi.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2cucijfzh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gt2pgywqevp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gt2tblhdemh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2fcdnpemv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2vzdjqnvc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2mlurfeot.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2nucssyzy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2vhtrgsuv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2istkgdvv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zwxgliqa.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2gdlznlsm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xrjtvmxx.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2waiqzwph.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2bofdjpas.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gt2cxhqcydy.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2lrjoribq.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2kdwseeva.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2zykchgqb.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2zxrncwzp.html


<!-- 参考信息 -->