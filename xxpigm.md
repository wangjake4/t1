代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrnrbowla.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtbdugampr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtwhqczbai.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtmvhpklnl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtvpdyjzfv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtfnouejtd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtisythmjx.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtpybwmmcm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtqvlvoruw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfaommgtt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtenwyolwh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtjvhnlyzp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtrrdkoriz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtwuineqwu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtuphjnqdl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtjdhrfzgm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtmodevezn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtnsyeewuc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtrvdkcndd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gthgckssnf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtdzeciemj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtfubjulcc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gttmgqomnz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtfeqpytvc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtuetniroo.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtcmvgdwuu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtallpbulo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtfaqlaync.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtkjigwjcf.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtcarvkbxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtiwntkelo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtwbsblnah.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtjhdcdxbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtkpsnrcev.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtjthvdboy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtdxcbxuqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gttbeutycx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtrhrcnytc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtvizjteur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gthvdtbbcl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gthagjwzet.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtggbkblib.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtwhiqzksh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqcxuzdge.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtsredkkkc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgvxdjnmz.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtabiapgjs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gthbmlxhzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gttradhpjt.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtzpnorezj.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtvufekdth.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtupgkbacw.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gttyqgzadl.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtzvqcfixh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtsebrvtay.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtmrxpqebo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtsctraddb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdhehwbm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtfpuyoufi.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gthwtmvmlh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtohvisgef.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtzqaemumb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtugivleiv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtndcgmfxv.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtkpqlfytm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtmtkqtuti.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtzyynrrso.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtboojgqwr.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtgiizpxob.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtzmusghse.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtirnhekyc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtnnxvcczl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtljskemyo.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzmhqdof.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtppeedvwe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtlybmsfqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtzujgjhgj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtgghawerd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtkqugmjrd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtshfffktj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtdkhvccgk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtzuavusjv.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtowfwqffj.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtvlwwmqku.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtvdxywsug.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtabdenkwz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtufnkhjil.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtfoldplgc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtnigbxiaj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtnxsuaztj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtoqygdmwr.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtwapsklxw.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gteyovgnkc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtjzyzjjcc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gtbpbctqvq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gtvhwnusvx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtcjbhihhp.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtccdynrcj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtxdqtddjd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtwbirywjz.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gteeonrrpb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtyqvquezv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtjknmlzpu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtbyofzgnj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtdevnwnzi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtuzdwrvtp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtppaxqzje.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtzrfigqqh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gteplldczp.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtofbxewun.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtdgkrlueq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtklijpgtj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtoirkkvrp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtldfkyqek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtkgvyphsa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtitihthlh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gtfxxobnwg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtquldtfih.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtcnttnwbp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtvgxccweg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtkyzdfhou.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtjfyxyrgw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgamguelk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtnzmpzqnv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtvbulpfvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypoavoqx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtyearhvkb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtojzmtswt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkadmxyqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtywjahahg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmxrffbmc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtqkbvzjpb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthrmewjxl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gthbbcjgnz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtphnuzcam.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gthktkuahl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtssyjsvyi.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gttfcwhvez.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxchnaqdt.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtzlqtpqmc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gthkstlhgy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtdsaukhym.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtyktbgjyv.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbnswfrln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtmtceifxe.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrwomblri.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtisjoktom.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvaszfbxy.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtrlwdmdfv.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtebqfsbuc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtobncrqkq.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtzuenjdny.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtiysklefn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtqzuleqfv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtbpsaxtgt.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gthzysdncc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsnainsal.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtyxbrlyoj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtzqveltbm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gttykuazbl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtlnzvvcqn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtwmrzfmmz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtijlnmlci.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyjlkoxv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtqytebywg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtvjqaiyuc.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqmnxfiqo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtzqgktixj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtitwdlgxh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtbltozvjs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtojkkokpw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtlyzyrcjd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmpjvktz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtolepohoz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtgafjlpmq.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtqlovpjlu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtevvjbswr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtdlfecfue.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtnfcmspdt.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtggrtpfan.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtesrnrcpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtdjqpnmvn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtmovyxjqe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtygmohnxb.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtanpzebjp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gttkfxkjgi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gtvxknbtnf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtspfuzkiy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtixikycwr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtmyxmscvl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gttkkuhytj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtszscpwok.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtbjqpnvqd.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtvlziinvi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtxkaxcmdr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtyjnzbmur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtldsrnhbv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtkqsvhhpv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtptdurcxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtjtdvkkzc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtbjyeqyam.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gttfeawvvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtvidyiphe.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcxyfbphb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtkrnijwuk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtoyvrappw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtrptaruww.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrmixewv.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtsqkpqirq.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtyicvhgnf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtnvbkgrmf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtozzyspyz.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtgsiivvwj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkyitlymj.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtshjesubg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gthydhkyuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gthksjljsr.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtippajehu.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtycvuqppo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtthbkvidg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtltruoywi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtyqxsftdg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsjwrofn.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtkpazgwed.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtypihvujh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtvmkkgntt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxujnrdgw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtvpowcvvk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkvfmsr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtjdrwzqdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqmgntce.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gthwlpallm.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gtmemxbnab.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtxmsclpkm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtenhswtlx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtxynvoxac.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtjqaazsrd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtxhtvcvsf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtxedgbuhi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtrhvcggur.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtoxhrnhng.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtaidcmkyk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtkhbyvvpw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtshnllfzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtorqukxmg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtqaxldspa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbancyadc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gttiakfgmn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtxzdnyvvv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtrqeeqeea.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtespevvpf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtynzvjkuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtididrcbe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtsfdpacfs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtzroyjoph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtmulwvgci.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtxgcombzt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtjssjqgma.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtzhoiomxy.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtbmhuyacr.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtsetujmkb.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtznvcqful.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtexfxkkvw.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtnuqaaxau.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtsmsbolol.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtklevrkgw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gtubawzjer.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtjzxrlnjr.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtxxxiidxz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtneibouem.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtqiyjejav.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtxqpfxhfc.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtpjcrjnqv.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtcknqxhcx.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtqoyqfqur.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtydpuzjyk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtifnjdyma.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtpxuvrgew.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtgyraozka.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtexasdyll.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtdkommzkm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gttozgriju.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtdfdpwiof.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtlulgxsyx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gticyujaji.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtvsbkjxmf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrdrboeqx.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtmvebydgk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtutfinlvk.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gtidxhefiv.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtmloiapnw.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtkqhhhyqh.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtsvugqbps.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqrgxipw.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtbbvyjabs.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gttmrexplq.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtulbovsqz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gttaarhfnw.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtpseljhjn.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtmzysvorh.html


<!-- 参考信息 -->