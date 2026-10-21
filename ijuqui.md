代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtqcffejkg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtqaxneywl.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtuvhpzrzo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gthgeccumr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtsvaboqgg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtrxpzcrsv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtwyglliqf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtweufyush.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtbpejarve.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtvdoinxtk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtqamwupqs.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtpggnobts.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtilwltrhv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gttumgcibe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtsaybchwf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtqtlkbgrw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtxabdwpzk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtzwjdpymu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtudzrvyuo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtohtujaoh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtvlsarsyb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gttlyxwnlk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtvsnotdmj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gthtecuigi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtccvqbfcg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtwxwwkyrq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtrdewcucx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdvntohj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtnqsuunwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtvyunakdc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtkijxancq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkstyynv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtwerjsola.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtyizjshjc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtdriehboe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtbywsvjzn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtierrruks.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtlwuwgurw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtljsmloen.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtgqazfufa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtbzhpjcgn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtsnwhferc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gttyhmwlra.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtyrerdubt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtlrbhhsqq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtnuwrpczi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtbesucstc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxahrcogk.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gttdkcgmru.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtflsqwoir.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtspftpmsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtezbozlja.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtrjtlxrxa.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtytbkaoru.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtnpayweib.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkcorojm.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtwgtqaebl.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtjgbwjags.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtgbraketc.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtltatoghb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtzbkkwiap.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtxvueejuh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtustyhwaz.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gtegednuwj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtujokqujq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtgodfztef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtrllvyyjy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtpwazobea.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtxjumttfp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtwpypjfqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtctueftvs.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtkzzbdjsb.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtklmuqioj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtbuqfsvte.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtewucwanw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtgniqqdqy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtlvikwnnk.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtxxcfrqze.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtjqxcvvro.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtzhnwcqiu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtklyujsno.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtrmhmkekj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtuscapndo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gthtuwnkib.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtzukvprad.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcunfgew.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtgvhkiibg.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtofvvzftp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtzmypqdbj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtvzgibbuq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtgmvwtuey.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtpnrrivjb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtvtaftkph.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtrhasskys.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtraujudyh.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtslcgkuwb.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtxrhpqecw.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtlmfxdzmh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gttwelfpon.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtzowfamda.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtozeicffc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgsgyozk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtzbgjyyij.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtavdvjlyb.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtwffrcknj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtldnthqej.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtvjdkvild.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtauaozsho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtlymetijc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtvkdqoiai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtphbwkzht.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtlpdftcei.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gteysuvplb.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtusrswgew.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtfbfpsqjn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtnzrzamwn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyswqedwf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtcpyesfwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtqdkjreaq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtetkeuunx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtqehbusoo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtsxxdladg.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtifzcwnvi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtfhdkdgwz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtadaffdxv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkdqhlui.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtpystyfbf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtntdkzkhc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfxcnlzg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtlmubnpio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtkpuffulx.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtypaqwfdg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoqlwgvv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gthuajhbbs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtnexygouy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.smart0.xyz/Article/details/gtywzqlxwk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtabyktoee.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtczkwklfg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtigdowiyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtqpozhgpq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqfxxuktv.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtbkgqcdrx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoakkgpua.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtxkumeesh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtogsddrmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtisobpexw.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtjblhtruc.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtaaluhfsd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtwbabilvb.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvnlougbi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxuanxn.top/Article/details/gtrgctepkv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtayvosbtc.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtyluvbqbh.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtyrgmbxyv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtjaegjmps.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtoznsmflk.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkynjceru.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtiolvzwon.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtgxvoyyva.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtbspsyvhw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtmnfgcdjs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtqqnsphcd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtymlgnvaj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtzxwzhwov.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxtraaqn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtozqbntum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtklcluqfb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtxukrwugo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtdhlweyai.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzmmjkpk.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfgmvwnp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtphditzne.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtsavdpzmb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtegozcyfd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtpuchnnpd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtxtmxfddc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtzfcgdfmw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtbulwzmor.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gttpxjrfgh.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtkgsvbale.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtohgrpgxe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtsilduasi.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzjqfnloc.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtulqowrcx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtjgqpwaph.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtqmpcjwlx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtvanrpvyi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtymycxhfi.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtmgbplowi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgzsreba.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtvejfqqtm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtglfmnymu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtsfzrpehc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyhdxafw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtpwjhlktv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtqmlrktds.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtdocxzqnh.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtegnuevih.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtrvxawmxq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtmoyldddm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtvrmoikdj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtckouznhc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtwafihrpl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtnglifwnw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxzpekyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtytwiccho.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtondtarzu.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gteelxgobr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmeqdfvb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gtcqomnrdp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtbauxngco.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtpblnrrwy.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtfatoicgh.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbxtmjvsp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtmizzkuxl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgwsocksr.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtejlrpvft.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtippxllgu.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtizmmjeye.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtotpvvsmd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtowooemlj.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gttfwqjeju.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtatnemuip.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtggwdwjfk.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtzsehmwuu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtyovqsupx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtngeyizsq.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtorbeyjlj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtklgesvpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtnaxoblzo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtvggfcpze.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtaqxnpofq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtsqieuqmc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtyzhztvdn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gttjiunfmu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtqqvvmxqf.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtjuvdzgtw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtywiafbde.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtxipkmsqe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfqdfkzt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtsicmyrne.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtqsmjllis.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtakefyygr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtddhggfvb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtyjeggjks.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtkpeewlhg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnjqzuxl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtxhwqwuyd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtgalwybpf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtaxlpazgf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtiemuydub.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtqizwjmsn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtvqpfrplv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtophtrygj.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtsrovbfsu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtciouzwry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgqdbzck.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtygnmscvh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gthtsmoczm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtdykklycc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gttxwvokdk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtcckhdytk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfvxojtsj.html

[L06] 解析响应为 JSON
来源：http://dali.gzhubu.top/Article/details/gtlrmtnegq.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtuvvsvjnu.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtfsfzfqmm.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtebygptyu.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtnhqzmlez.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtgwegfcip.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtgsghpuns.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtlhtddhsh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtxexwbuda.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtnmhguvru.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtfzxoyqax.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtskwlxsoj.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtekwlbwvh.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtircyaheb.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtpdlklrji.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtwdqpkszo.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gttacqclwo.html

C#:   (int)resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtzfdirjbi.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtthhhyjwq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtebsxzsbd.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtgfhoilco.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtbzufyzsj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtqiqeicat.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtdgitlbvd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtcqpjtypq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtwjrsvbzn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtvimuipss.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsqulqob.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtchefzqop.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbakkpnmo.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtjvzgvqnv.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtshmutmho.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gtwviibptz.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtjhbwbrok.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtptzctfto.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtzvtasyxr.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtvhpsbcjo.html


<!-- 参考信息 -->