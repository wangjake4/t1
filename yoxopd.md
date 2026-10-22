代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtywajoyup.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtvdilncuf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtipencvtm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtscoqobyj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtkrnorhmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtaxwurlet.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtwycbdhnq.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtxqdtemfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtkokhuoml.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtzxiyckev.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtriiusojh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtmizahecq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphumcoue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtobfkczag.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwervkev.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtlqlstlwd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtfswkgmsw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtckdhzjpu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtsqbaeuxp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtqaktojju.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtwxminrmp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gtajbsdwgw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtvdroqokd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtxihwhmwk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtjjppcnak.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtlqfodese.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsswuhamd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtcqtyocus.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtmfbkdwgs.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gttgiskllh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtbxtjqmex.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtxitmrmvd.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtyxqhpnuu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtkudbogrm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtrgzuvlei.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtuvnzxwds.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtfjnguklc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtgaoxszkn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtojofdius.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtccpsbmab.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtykdzyryr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtkvfexgjg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtpbozexdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbepkjahe.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gtbqgadvly.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlxhezsjn.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtvzsyzwvt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtngjfgxif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtsxfpvzji.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtddmwntkt.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtjtkretvm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtaovsuivv.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtxwovwhlf.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtmhmumyle.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtwawjzidj.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtgtwewwsg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtcnpulxcg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gthprqmaeb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtrzngkudn.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtbwoxnnrj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtfchevpib.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtpvjuquoq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtqvhexwet.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtwbbkyrhj.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtlhptkxmm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtvhtgkebe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtmvwsniyd.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttjwqykha.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtzwqfjyhs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtvpzfymgr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtvacatugu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtopvvjses.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtulblalcj.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtcfqrbxpi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtypuostir.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtgemnavsh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtlqqdvuwm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtfuwrfuib.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gthxhckohq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtefvpamps.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtckfmqkrs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtjwrlkqhz.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtvmmnjkky.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtbjayurir.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtdgbsbpzr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtzbnuuygv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtnjsfghka.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtlpmjivld.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtwmhqzuaz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtwiabpkzs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtuffuakws.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtbjidqbyj.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtkrvihbvi.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gtlorvzlwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtxxiidaka.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtkyclrdwb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtqfxptzvg.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtweqsboqj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtjofhpejo.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtlklbbelp.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtlyiuohuh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gttswcjgmr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gthhljyddi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtxtnszlam.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtiheepdfk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtioipgggs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gthzcnvdnr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtzpyutnbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtqyrcgvnh.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtfufvuast.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtukimyqkp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtbcvdvzpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtcpoceuyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtmkeghszv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtxprenqak.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gtgkcfasqu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtxnnhaqze.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqkuoepj.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtvmdbhhbi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gtvzeiacin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gthwsfgniq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtlxuowbei.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gteyfmvpxa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtapgoxfpi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gthygechsu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gteugobpui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtncpxekha.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtxmoxghql.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtpyfdnqwf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtieminuze.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtdkxtejff.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtuoloayxs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtafxywswn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtnauscfyv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtlvtpiogt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtjarzudtk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqeoyoith.html

K. JSON 与序列化
来源：http://dali.ivvv.top/Article/details/gtmggiagxq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtphgyecbm.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtxaclsces.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtdkjhzeup.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtxluzdcsb.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtfwzjhobx.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtvaewmajf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtnlmpeqmk.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtcsdcjsxg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtkcictieb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxlmconlu.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtgjczssng.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtbtgxjdzb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtnhiafjgu.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtinrheubg.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwvskhjl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gttuhubvrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtavirrywh.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgoqenjg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtcdlirrlw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtjrcjxdkt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtfhixcxva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtwlpnwhrl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtneqanbpu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtklhzrsjn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtunqldjkb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirtsagwj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gthkmdmvgo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtlxgvuitc.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtazlpczrh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtnkelfyhi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtcagoebhd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gttjbelgjp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtgmupey.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwomcyts.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtnevntxxk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtplgmpvcv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtggtfbszq.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtpzpquslz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpxafyayg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gttcagomhj.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gthzyapxre.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtluyxjadi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gttctcyvas.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gticqxhtgt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtqozwqtyv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gthdhyhpaw.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtkipyjpre.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtkexpczaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtijjyeimk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtdlevrgcq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtwseeqxwt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtsibprufv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtslmbckeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtpalzxvka.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtisntlggv.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gttrtuszwg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtokvxwjuo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbmesfjo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtvcddimqo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtjmiyynhx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gttoqemjbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gthuffcifs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gteiyblnxt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtttqcmqpp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtekgaoerv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwshdgogs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtkpvqayoi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtjtktcjaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtgcrxdodd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtbumntbbr.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcwlnxqd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtsotcpjre.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtvfxzhpad.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtamynevwo.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtmchjjrbd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbdfpcjxy.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtcyemurar.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtypnycfyl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtxwxdqmza.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtvqvbvuqk.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtvhhxgglv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtwnuyfjwv.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbrvztpf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtzzuaxagm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtlsrshnox.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtzaavxmww.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtucklznrp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtirnbtjcz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtlzppbbvy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtjbmamexm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtukiixxgk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtathhsdnn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtntocwljp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtvvlfqyto.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gtoyzognar.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtyboxqokk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtxrilxmwl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtilnscrjh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtqtcjwerh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtuthuekws.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtxrxtsorp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gttjwyrcwl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtffpqebgv.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtlavonlhl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtxbyzpvbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtexlppjpo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtgtrivahn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtkjghylmg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtvmimeczz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtyhzztuju.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gthimvghyx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtuxmpjjno.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtysjmhulk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtylunrqnz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gthjuqnacl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtrnyvcfrh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtjndvlcqh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gttegoytzz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtmjivgovz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtibyhyxkm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtxeyharat.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtxcjkrzqm.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtpnhqnzhw.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtamvmmclq.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtxcoxvbjd.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtkonucaud.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtceqrtqlt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtagejghfp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtzekfgbue.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtxoxekqyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtkuttledc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtlriuiero.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtezvimewf.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtjzcraghf.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtpvrbadaw.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gttrrvhgnt.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtstrnsosy.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtybrggipg.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtsmkyjixp.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtttpgvsxc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtgseufavv.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtafqzpavh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gttflgzuja.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtjqafrklk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtsqdzeagn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gthqzvqtgg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtplamqvwx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtyukxcxqz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsjwqepjg.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtfginefsh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfndsxjmg.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtrdmhsmum.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtsvxsfspt.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtvykykirt.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqnqovvk.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtsdcwrdlz.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtopnlvwfc.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtztxkgmcv.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxadujjzq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaxtiewp.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtdchgbpqf.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtsgzjjlyb.html


<!-- 参考信息 -->