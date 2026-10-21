代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtfdngyyrh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtaireonod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtfiarfgdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gthkciyhvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtcbojpwpq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtmlgwdgkg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtjexbpwyt.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtbnktvsov.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtuasidlyi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtnuiaemge.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gttjlszjyt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtzjxmudrh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtlmecefpc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtyrvqmlib.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtcwpluylu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gtgyfmskxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtuqmhdyxr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gthlnltdcl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gthmzuzbhw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtnisfoxub.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtbqcwcvet.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gthhvfqagn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtdavmfkbs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtnnirgnzt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtxxxswivg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtvhanvtey.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlllahrv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtzqfdupcc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtssljugog.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtcszpfivp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrjkcryg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtayhyaeto.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtmhiguszt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtgbpnqgyh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtawdaofap.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtnjrdjmua.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtxhdozrbq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtnxckvnif.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtpgkemtfk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtzxtadlqm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtrkwfurnq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gtclsgimne.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtomqyeell.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtblvvkxop.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdybvfnoh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttblqjkhc.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtdrynzpfv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtmrcnvsrv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtuyndxhcp.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtdsfquwnv.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtvrotulcf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtjrrarhov.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtajbuhswt.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtcgpebfay.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtshnmarto.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtkrxppbxs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtnkbnjnto.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtztuenmxi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtwnmnulfj.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtahbyizbu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtbegqrtos.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtykvfkpid.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtypkpdygf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtbxskkbfl.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gthutkxuyf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtbgudadyt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtfzdfqugd.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtlbdqzrfi.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtwlwvpnmi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtcueqaedr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtlwugoray.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtkpwybfwy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnplnkbto.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtvqwhkbla.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtvimyeldx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtlrlccvcj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqegbvgf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtaeekzbzs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtmzvdhwwc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtamaalthd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gthfdcuput.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtnfqvuetk.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gthrvvekya.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gtttzjpsfv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gtysgahrln.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtnvoymenv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtgjcdnutj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtbjafhaiv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtisbghrsh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtrwubcfzr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtjewsvefi.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtmgirhhmt.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueimwtqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtyqijbllr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtbjinmqgb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtfxrxdhgf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtxhpnsshw.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtaxfkiwko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gttchcyqwl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtczyltzcp.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtmgxpbxps.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtnhyuzuhx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtkdfwicxr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtwxekmxkx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gthynajtll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gteevuozfk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtdwddzryp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtdekryhia.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtrjgszgmp.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtiagufnfm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtrfmyeuty.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtszimvuoy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtrjfzcmxh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtlqhvwkpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtdhjddlpb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtnsiovzej.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoruoxkky.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgrszply.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtxywgmcto.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gtapnfycpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gthaoveljt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtkzoyumho.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtvflcuysd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gttiigveav.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtlfpxfsae.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwylxcfc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtdiqxflao.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtgecizrjk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtifcjrqxa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtmonghwzs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhilqviw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gttuzcdoqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtznlmselw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtumegfcop.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtownestmo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdxkalpk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqiqbivbr.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gteeqlozad.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbcaqcbbs.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtqgolwnvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtqahhktjk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtdboeowxq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgtwdupnd.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtirkytrhm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtnmydsesw.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gttyhhygfk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpflmluzn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtywpifhpx.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtbnddylzg.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdhohyvo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtfztthwly.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gthvgglgny.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmecxudxw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtusszuzsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtdrvltoxl.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtiiglbedm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtpfkoabfx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtlvlembym.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtwywqbxut.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtbmhuebjf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtijdwcqba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtgukpylat.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtjpfqnwwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfydtmnq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtdgisrbic.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtpdovlxol.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtsjetstvi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtsrnyzzvr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtsjkcwyfx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtcylkkvar.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtevrminyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtgxeerbpx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtbkkrqmly.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtarizzrez.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtxuibofki.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtrvprwobz.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtvetchced.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtgansdgdz.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtvorsowqr.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtvyejnemm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaazrynho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtfroybndb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtchjbcten.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtnlgrqkbf.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtwjreaqlp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtsxliufre.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtekstwjzc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesoplwzf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtreshzrfw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtuhogqpyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtzicxtqgi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtayspftre.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtayrrkgck.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtvrdntcja.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtbxtfucdq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtptkaevkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtxmzcaugl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtgrbvzjxt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtgozwjxjq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gttkoqctrb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gtjwicjjnj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtljopkzlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtnexbhsgj.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtrjokpmqm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtpfqkvfnl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gterhjikyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtxspugvuo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtrgzyordj.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtumfpafiw.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmehlkxui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtxxvqzoyh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkrnyiywr.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtkxowraej.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnrqlvmvd.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtshsrxpur.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtjamtlmgf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbdknvjm.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtupncyqrh.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtmqpbmben.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtxgltjpzr.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtsqwewzqw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gthsidtlwo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtlzmhsmuw.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtrehvwcgi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtlwyqxwco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtpwropwgt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtxvomdcey.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtvhvswoej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtpmtfkfcx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtsupgpvzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtsdgcthek.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtdwsxodqt.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtrunawxwj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtkemvpwgm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtaohufrnp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtnceprcee.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtnamqxsgl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtsebwsmhn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtaiegipjc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gteuwcfist.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtccitdzbt.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtrtyvlpge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtwcotaafw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtasxatnnc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtyixtaycy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtoloozamf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gttsrsbfax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtufrdsrfq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtyaunxbzf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtuvfmpipz.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcazqnlsg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtaqggzuhr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtidsexquf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtjtjhuwlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtfalxwjvx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtxxpmwibh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtcimjffmd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtzbijwvyx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteywports.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gthseyatvk.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gtxrfmamse.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtkfvvepof.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtvcjchwmk.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtbbtykjgs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtnbzlkozj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtnermpvxc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtmbofiukt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtusqgsbco.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtrcvmrzym.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtafqqdism.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtdjlhekdk.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtpamtqvhh.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtoxnncfdp.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gttbvdnvkn.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtvvgsafeu.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtyqkicbli.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtmljnibie.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtjxqwmoyt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtazfnyvuz.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtsmzccwba.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtjsrslnoh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtabtiasbf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gttyahhgxo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtwdfcxmlp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtvclhqzao.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gtwdswlvif.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtduckwfdy.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtpkdzrlty.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthgqwjyol.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtzpzulfze.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtibeppfwl.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtarkuyqot.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtajrfzvbk.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtujsmocrt.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtzjlykwjr.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtxmosouut.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtanqtmmhe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtqwgunjmz.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtpwjvbfca.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtpfeyzcaj.html


<!-- 参考信息 -->