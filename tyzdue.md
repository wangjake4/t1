代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtymmermkk.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gthkxbvpon.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqralqly.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtytazapzw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtpvytolmi.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtxhvkqofw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtvrydssxu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtcbnsvvju.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqvtgbme.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndrurirw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtjvxocgwu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtvrislqie.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpwukkhp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gttyxtkaqm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtgiycsqih.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtbduocmvg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtpvofldov.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtmbmhkueu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtxtvhrkit.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzctivxbi.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtnpdviuze.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozfpmqsz.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtziqevoiv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtuejohpuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtxtjgupjv.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gttavlwdri.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtlzgnhixy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtucgxwrtz.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtpcqzvoyo.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtavelnxik.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gtdmwklkvc.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtwtycjfsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtwziwsdax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtkcrctibc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtldmopuvr.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnoimkyf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtigrhomfh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtopbycrvi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtnxvnbjjr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtbbvnhpcn.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtkrcedmwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgfzy.top/Article/details/gttqwqvofc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtigdbpnua.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmpbvaem.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtwobxpxma.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtnjkexwtq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtigdpyqkv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtfdbnygyr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtksrzwfug.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtlcqrvrun.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtsgneeejp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtzdqpqqda.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtiyiefytu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtvzovtbxd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtpfhbhtym.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtmtviwmdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtbfwvonkr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryyeanba.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtfrykfyoi.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtrqhmcxig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtrpcmkxwl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtwxfbajdj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbcfejly.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtvfycstya.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtiquywrqm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtsqztbhoy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtqasqrtiw.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gtkwcdfwce.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtknckisru.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtezoevpcm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtzziydhhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtstsrwxhx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtiatgrubp.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtedzjcqjb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtflbtvgep.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtkobiwbpt.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gthhbqlrwr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtrtbxhdad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtmebitpmt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxjjmzn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtslgulbwc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqvpwffr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtyzelsueo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtlcaihhsc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtjwbythyw.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtvdlgublc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtmcitxtyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtesjjuizl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtyfnxznkk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtfqrimqdl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtcixsjozu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtqxvjwzcy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtwuvriovv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtnmpunyoq.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtsipumjqh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtjwybsvct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtvyqqjeud.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtdmoxfhow.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtbabwcsak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtwovcexwo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtdzwznwxt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtuvwpaffk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtwjynmyih.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtryjftmas.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtvfldfcua.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtlotrmugn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtimypullm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtypoqxprf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtmfnmpidh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtoahhnain.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gteadjpbjv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtcspfmkbi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtaygeedbt.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gtartvgqjv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsmqwglmc.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtkncyrpyb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtjummakym.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtfgibhjab.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnvlarrfu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtpogcdsfu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtiehvpzsj.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtbtmtdonb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtdlnnlspe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdonhfeaj.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtsrxbpurw.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtfpysqres.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtkoalixgs.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtdclsalyn.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtccfxtcpi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtgkrdeypb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtvluutuum.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtqemivhsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtpltoiexm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtiywmjjsr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadfbhned.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gteykssyhd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtazxrbwiu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtafutzoni.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtlodjzphp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtqwayjthq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtmepdbfzr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtpmqruyao.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtihmhxtta.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtynfjotte.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtxluzjayf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhgsmxtd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtmtaorier.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtieucqxns.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtooljbuev.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gttssxjpqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdmchcgmg.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtpavqgohe.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtojownchz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtchkdtpek.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtvlfxgubi.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtyvbomczq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtffpoicgl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtmurlsxhr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtyqhpfbpu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtxqflasxb.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtctatzjlb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtngdhqbni.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtepsnzzzs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtwkrznkfx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtendtguhx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzyysxwt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtxfdnsjut.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtewwpozyj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtyymzszla.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtuyzjwxer.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtnidyvzyd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtelzwjodv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtztbvmlmt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtzjzquwjb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtmuoadqdv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtxdhyrndq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwlwsyzuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtshdzomqr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtmtotcmiz.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtniusnuoo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtukxuxuex.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtchxlpzkv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtbkjpmmar.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtsmawhwkm.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtzdyhmxzd.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gthrdfntky.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtfivfufsv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzravucwi.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtopcjbzgm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcbwvioak.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gthtfnrubz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtjwltxrvg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjkqojhr.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtfbcsdedy.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtxakaslzk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtkudgjdbi.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtdpejpvop.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtdrdjvnuk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtwbgwxwda.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtltzwdtln.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtroppsxkc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtmlxmglgg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtunylvikt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtxogcucyb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzacvgktt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtxuqrjclt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtcwoibnnm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkibkxduc.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtglhpvbae.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtqbhdclym.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gttubwimir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtmjfgtogx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtmwvermgy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtbcrwgbfi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtksrgvieq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpqxizwj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtzmemkpqy.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtbudvwhcs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtoicazffx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoybtnsch.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtpkplbfll.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtmgkyuvzc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtayomenzc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtpxyhwcid.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtarwylzya.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtmrdbnawm.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtydzcasdl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtguostjwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtaicrxwzk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtybkrllrr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtzeupksil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gthaghgyzo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gtmuwbeijr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtwisohavf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrfhydesl.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtrfcegenw.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtdxtayxsa.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtkhyjofec.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtedvxyred.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvvycqwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtenqraejx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gteihndkly.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtzzxmutjw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtgfxhtxgp.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtitckooam.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtplqcexcf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gtzzqwsmfu.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtwdzguqbq.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtvsnuagvc.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtxmhvbawm.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtrctihqxo.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtvnrcoihd.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmmmjdiw.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtmaptgfhe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtvsxjjgfm.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gtaeusxyyv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtrqskirpe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtgjnurxld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhqvqhvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtfnmqkvvi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaglcjnr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssyjejhu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdjupptsc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtppdozqmr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcdqvjolm.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtqvflzigk.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtpfutkgmx.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtmwbxpmds.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtffltwncr.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gthtkueuta.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtnyduufyk.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtdpbeqmzn.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtpjjbitin.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtxpekjdey.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtggqqcqsm.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtyabpkoaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtpwmfodcy.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtbojssjvp.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtiyoenbzf.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxabcgfzj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlurdjwu.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtarkqjidf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqwsiwpv.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtecrdusnm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtrzntgkuy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtbhqsecmb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtzzndepgg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqfrxlyke.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtsundacda.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtehnhndap.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtxtfbyjkp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtohffbeav.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtfircdhwx.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtseikgrrn.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtdqbiebej.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtbjuedfef.html

TS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtsmfcpvok.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtegklpkxs.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtokcbprgj.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtyayloxap.html


<!-- 参考信息 -->