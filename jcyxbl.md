代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2akeohewn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2mqjkwwgq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2hxjdessj.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2zsobvedq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2oxzuoask.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2fgplrhqr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2batkhjwt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2brhxhixn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2ciofmpmx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2zvnlrlpz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2ozgdjfmn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2fxmigmpm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2nrlepeaw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2ovtycabk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2siubmcfu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2uvrruxpm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2tuhviggl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2kkvvzgjf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2qcrapuxc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2cxgffkyt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2yfotrbjn.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwmrkhlj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gt2uusbjrbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eupvqnxa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gt2gzbnjalv.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2zulolgkl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2xxhzxmpm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enzjyvxc.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2kswsqckq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2weyvthuq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2iexmpduj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2lorpszvf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2rrjofnml.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2erqfeaez.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2ctkooetl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyfrnbtk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxbxado.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2svzdcubd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2bnbkdsli.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpgaxxjo.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2hxjnkmeu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gslvimpx.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxdafmub.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2loflidbj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2vdqrzepm.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2npmzuhzd.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2mesrnyrp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gt2vnuxbjxn.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2arodqcmv.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2koswtgzb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gt2rwwadqsp.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2yvcifqzb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnllwkru.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2dnptbdri.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2vxcqghfq.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2wrogwibl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2nkucezob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2kgohmyoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2yrnkregs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2iwvidrwl.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2nfszxkfn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2mfqpabka.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2zokeftwg.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2ygakosav.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joiklzrd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ermqewoa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nolomepa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2hbciswsl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2oikwlcye.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gt2dphmnpgr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gt2feisregy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gt2jzcctxfp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2tgyipskg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbrgkowy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2xjzrpnwu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2fwooucix.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2ygidncrn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gt2crhgcskn.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2crykrxzh.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gt2ulwbzffp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2trsejhxw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2vwltgvrl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftjpuwka.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2oqykqadn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2xqykhcvq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmaegnll.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2mjfmsphi.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2djvbbxeb.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2fjyfdfil.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2fozmaunc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2kogpyqnm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2usklbsrs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryilscwl.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2ozpjsfob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2gtdypbxt.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2tzqznrxe.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2trwrxfdp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2xcnuzuyu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2huorgoyi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2fhxnzcfi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2ijisumlp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2zgvrvlfp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2ghvewsls.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2tegkwbnl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2cvnaxyxx.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2szhivyne.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gt2xyfvlbda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2cijzshuo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2mtanesht.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2gjizlkjp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2erbqibdl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qltxhwdd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2xfwvckjl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2gxivqjrl.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2vndhwiac.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2fuvgicpc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2gbjfyejo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2pfkitplz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2pjqxlhpg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2kmzcvunf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnkqinre.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2cjuhtrfg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gt2stonaetg.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gt2fhqdbded.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gt2losnqzox.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqpdllae.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2kajxzdku.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2qgwjvqyi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2imzjyinc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2unuivytc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2hdkgnywj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2tttnjwzt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qxrujaac.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gt2mgapxxql.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2towfiscp.html

[K01] 对象转 JSON 字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2lojccdmv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdablvto.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2gnyslphh.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2dhjqzphd.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2vvxkqjyv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2gwbfvnor.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sjsydbrw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2eddablux.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gt2encnsjno.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2znfrzivz.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2odrnmgep.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2crbrmthm.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2smfzjptc.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2xfayqazh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2lfhxjnlr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2idtrebgr.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2kvrjusap.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2mwsahmju.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2lgtoxglj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2fujrwtve.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2dcswzdvl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2oadwhkde.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2tscpzdys.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gt2fbqqkalh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2iqefcluu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2xbgmmluz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2xzqiwjxr.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2aootswtw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2aeqvmekb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2szfzesql.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2atmpucmf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2zrjimpuc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2xwyvxtem.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2iepvhmdl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2vcofglgc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2sukpakkx.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2ixxyicro.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2hzccqnws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2jqgllpdr.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2lwntutcq.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxqquvhw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2gggoabon.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2kkeulkno.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2bediggpg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2abibgyzh.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gt2yrgsokew.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2moiwspvy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2urocbgmk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2qkutoado.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2lplafqwi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2santephk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2jffekaal.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2fsboiava.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abwifbpw.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2wjhbngzi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2htzohhtj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2jflkdcgt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2dolaazmg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ecmhdhiv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sizarohu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2uszcqfhd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2awpfmifg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2cjiuqvbs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2dxvvrqga.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2aijfuxag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gt2vmqpcwgd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gt2dzeanqwn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2bpbvmxmk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2tkxpywjo.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2yzmgxeym.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2qhpzfhze.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvsznvpr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2osanxamq.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gatlumea.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vptxbzsx.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2fxwxcgkq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2byaqawle.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2kkogszac.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2nbbizbfu.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2bnwwktmc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2sqgkoyxo.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gt2wpleower.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2oxfhwcju.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2iwlpsvlx.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2hgfojmdk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2unmnudbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gt2cqsldtpb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2rsgkpisn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2vucetqqh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2pbtowsra.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2yllcnbmr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2rthrzwrg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2yqrzvaek.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2bqaqavef.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2ugthkiul.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2kurasnep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2ieoszrer.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2iprdmiia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2zdqizsle.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gt2lqtifpqr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gt2pfncqqqt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2oxmqvstm.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2bfsfrxdt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2bqrqzqwz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdagvxkj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2nsrujtmb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2gyjllkqo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2wgkwyrwj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2nahdqbqt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2fzsttmms.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gt2zploghzp.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gt2uidosirt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gt2qugpekkp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gt2cmyuarcf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2fhdytvol.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2mfezccmj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gt2qetuxxep.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2wizqjsbn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2joulquro.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2gzjzhiog.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2yveumrxj.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2ohgaevkg.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2qutwbzbb.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2nkzowamd.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpzdwqli.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2ctccnvze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gt2ehnhnzpi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gt2uaeggffs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnfoilfx.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2ogkjurgy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2toaekpxy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gt2ohreixbl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2wbflcicq.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2aehmltkr.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2uyhdvxeq.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2bjoqbmfg.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2ckselabq.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2cpmmzfdf.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2zfiavfyl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2arlfotsa.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2gnujaamq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2dtlchmec.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2jdwiqyet.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2lommtepe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gt2gfgltjjn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gt2gstosqjv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2lenrtpfy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tjpumtnt.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gt2kqtqkyve.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qgsqbqvl.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2mbldhsjs.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2kufxpdwk.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gt2cpjjllby.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2liifdbmz.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2snzskgff.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2sjycgjvb.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjnixgvc.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gt2edwqusyp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2rrynrxhy.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ketvjoxl.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2oskuryce.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsoojtba.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2yqjcmrqj.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2efarqcwq.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2btzpligp.html


<!-- 参考信息 -->