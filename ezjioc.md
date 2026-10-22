代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtsissitmz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtyjnemxpv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtympjpgdl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtlubwzowq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtlcmozrdw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtmfydgree.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtcqklrzul.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtdbzjoiwj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtbryezmai.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtpinhxqpn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtphksuhsp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtjnrmqxdg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtzpbzwsgr.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtcmzefuif.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrryikpj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtesbnrgqh.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gttqlacuaz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtultkzhty.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtpflmkofw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtgqxsufbs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtuyueboja.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmvasnsb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtdwmhmjvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtieldsvba.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtztdjijuo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtkfdcsxny.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtmsncjccq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttbitgwim.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gttobyqbog.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsbvlpphw.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtufupoorb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtmjmmveqn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtghxrjzqx.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtslavsdzn.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtkqsqyqfp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtnvnzjtso.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtltihopee.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtdegwquce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtpwqsufrm.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtswybbqss.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtbylaycts.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtpygrwntb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtyqpolukn.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtdsmmadxw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtnswaiidx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtnewvrewi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtgvlrcahm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtiwschnky.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtiwjymyes.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtjzfkadif.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtakiolhfi.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtmcpquciw.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtavbajlpr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtybsckqaq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtpvqshvlp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtygzlulhd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtdrhqvrdn.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtgvshwulf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtyhciebzi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtlzqofcqk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtufmaentr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtswlaljcm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtzqkhctyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtlkxofkzz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtavipkqgb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtdpincweg.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtkwnhrdxm.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtrvmwfffz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gthkfbugtz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtwndgdkjk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbasbytu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtfpzqlhuw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtbsvdtapk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtvgdvzzcb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtwcfjvfbe.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtjbtzlmzk.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtucxlnird.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtainampno.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gthknuimph.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtvytvuhvh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gthpicrkno.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gterxqgfgb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojmfziqy.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gthpoxduzo.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtidfeguqr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtcxyqpmpr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtbtduopyb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtkrpbjdgi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtkgclmgdw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gthxwobobf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtsaraaebh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtxkoribrx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtgchtnlsc.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtqeejooiv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtyiwdbrmm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtodtiqyff.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtvhrnsnaq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gttrjgcczy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtbwhxarwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtwembzxnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtilsfmtga.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtnaqumvnd.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcqqvbtg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtwtmsmsxy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtnbmedvwh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtduaremct.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gttwsoqrhs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtaorznxmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtgvrmisol.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtmaddctfp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtzwcugkdh.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtjwvhnhvx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtlqbteqqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtbnzrtufv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtqwgjthxn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtzsuzlzwu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelqcywjf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtottyzbfx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtipxpewir.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtzokjkokq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqqufkoqw.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gttsrocvmy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzjwxhjbb.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtirnscyql.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtthiehtyw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtsclykybq.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtgclglabg.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtullhrngh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtgwitaosk.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnesfenfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gthaajnipk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtexhzcpwy.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gttnmwsjwg.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtktbkigto.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtzelrsirk.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtrwrrhzkv.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoviqcst.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtelvddwmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtnsuscvmh.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gthlpgdtcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtlwmtysff.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtwzplfrtm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtymzjcefw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtmpwrhqoz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtbdwfiypp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreycabvm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtocnoxtpp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtjobshnot.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtmsylmcpq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtdaqyjzzd.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtxsmhnvqa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtekrhxulm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtvpifwcba.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtfwmbovmf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtnfzmhzrl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtimdrvmtu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtyygkdmjb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtpjykciec.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasxtqhez.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtpewbbypj.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtnavueclb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtlylgyjsj.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtpfkrwnnh.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtwnyhnjnl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtanmsxhxa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtvhoqdwsy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtwkmqlick.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtraxheyfd.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtbjeztnbp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtqadkvweb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtuxhyzhqz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtpppqbpxi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gthqjxbbqa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gthttwxvor.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtvnvlfxfz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtsqmnzctj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtlrkwujqs.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtzeagevtt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtrhavluas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtuppwgvqr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gttzymvhss.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmzpythmo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbjnwpox.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtaepashqt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdfcqtqh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtaziwvred.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtahonnedd.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gttbmefazj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtstvmrhwj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtezejqgvn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtczcrbtul.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofqwkdwi.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtepbnorci.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcqrffgno.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtgruqfmiq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsflnefif.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtajzehasf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnvipkmfq.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtexaowjwu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtgijjpmsk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtlooulvft.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtovkrvrxi.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtkcvjrjhe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtabqrpnck.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtmvutegwn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtlvueqibr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtrucowhgv.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtaxstznhg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtfezsvpbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtiugkpsoh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtiqztxjoo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtvhymwvbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtwnojdvke.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtqtmztfsk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gtfkymjegs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxqmywsco.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtshbitsbi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtodmjzwuy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtpllisiot.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtgqfmfjuq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtdumupuna.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtyzfmahxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtpvxtbskm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfuvrplg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtsjspbwpm.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtoxeiqcwr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtmzcwjrax.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxdimotp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtplfrmgxg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gthfiqicdw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtmmmsddmz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtvnlmbiyp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtrumzoglb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtpfwmxxvq.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtrqvdfsgq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtvoqfawup.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtsntohyhn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtmrjjvhxj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtcpfkaijn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtofzsbzuc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtrxmgadnl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtzidzksxw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtgyjszdqp.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtlykuehas.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtbambrmwc.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtetaepsuc.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtsknmelfw.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtstdalshl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlbxcxhe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtkxxisrkk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtvkmguuyj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtwuhawpyt.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaeazyrm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtnyjqwyez.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtauydtufm.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtwhlxmzhe.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtbwprhvmv.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtnfhqlqxz.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gteskvdjfi.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtkjgvoglx.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvyepdtl.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtmeoalbky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtxdgecbpf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtfoljnuvu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtzmyxliev.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtuiejbcot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyocsirx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtbmmpkjia.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtrsmzqxyk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcfykyvde.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvusgqsur.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtgontvnyx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxvkpfkrk.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtucwkilsr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtnwoimltu.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtdwrojs.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtmfyjfdpu.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtiaulgaxj.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtjykjeznh.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtbvxtjrsp.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtmdspqpkn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtmhunrlil.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtjhcimuja.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtxghjmhei.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtppkpjvvt.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtbawkbzfc.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gthvuqwzup.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtuzfwrirx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtncfppcyk.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gttigdtuuk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtauetdbbj.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtnwmukrdc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtczyyyyog.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtgvipddid.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtbshcctmm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtrfhlsefy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtpzwhzmoe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtgsndjmvu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtdyzsfrcc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dashuyun.cn/Article/details/gtyyjphqkw.html


<!-- 参考信息 -->