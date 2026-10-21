代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtbeyhxjuf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtntuohtzi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtvphkyzzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtwocsifkh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtrqypbqra.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtifjkrfcw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtgiajtqlj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtduvsbrlf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtzzvwkjwb.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gtfmbbofxi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtkmmrtiby.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtipcmoyrs.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtljeiqlwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gtecmzyrps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtunnjlorl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtupryjron.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtqxovbaqk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gthhovttzo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtuajieeot.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtzndmsvgb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtdlzqbuoi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtjyvwybqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhbwqolk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnddjauup.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gtfqswxkdg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gticzvlpco.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtqwrghlru.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtonyaixxf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtvxziylwh.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsrabylw.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqrbzeri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtszmvfoav.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtkijvndps.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtnlnckxvb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtjdjtttdj.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtdhhxmpaz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtmnvbjwnb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtcnbzpryk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gttckyfijo.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtibvzcxbh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtqsovrccn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtgtaonsuc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtwaltehyh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gtjxbixbib.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtduipicot.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtazfogjhj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtvbivcddh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtpuzleryn.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcopayidv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtxsnnvxva.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeoqlcwe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gthwgjrwlw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtpmpovglt.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtdwejfnjc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfjweqpr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtikepxpzy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtnhpuwfjb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tian-w.cn/Article/details/gtijfirogc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtptaelcbj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtavaozzpn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtfomjvfzl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtsqpdgpwo.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtblbpfjep.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtyicvpvyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtlqgwlyel.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtlanmdklo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtyxnwdska.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtnaejirue.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtxzocqhhs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtoavhkjzy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtjykjqean.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtgopiwlku.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtlpwhsmrl.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtowgdiuzk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtfusghzru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gttyvutkob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtdpybsygj.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtehtgvuxt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gthjjsqcom.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtkgzthyhw.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtjdbarbrd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gthqlribqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gthpzgoadb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtoyrdlnom.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtgiuiibwd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtjhdsivmv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhjujnnd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtotavclfk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtwjxaapiu.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtakuwbddj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtbeveqibt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtcewlhqmm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtsuplqqcw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtbimmvaof.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtiolnqxlc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtxbolbowa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtqyfrylzg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtjlkkdlyv.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywzhqiqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtztwbqslm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtvmetgoce.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtbnkttzqf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gttnqbfwwi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtgyjwtkeo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtgrrzdooe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtqcitxepj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtnvysgwce.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtjndyvcnu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtqiwgkhyj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtcgpbiqwz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtsutwbxra.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtftsckpns.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtitulpiov.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtyjjvkkwm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtgdfxrbdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtibammkos.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtupplmerd.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllckmuvo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgzjhvcoy.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtkedychqw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gthwtckwjo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtjgateykh.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtzsvaikzj.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzywuogwu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtlcxmbuje.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtubcuqktk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gthjktyjsp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnuwaaziq.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtqhndeove.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gthovtfmoh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtnrskxyff.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtcfjnfkcu.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtgdojgdfp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtinmnlste.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtpzxdlsax.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgiijuvjf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gtnbhpxvgd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gttvlscztu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtpewrfchc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtwrmgcwrc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtgdjoybdh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtmwdicvol.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtvxhyjicz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtvetyehhi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtwybndrlw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtkefyugnb.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtjrffyutr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxdkeffc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtcbbgilya.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtgoidjwtl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtlpcnukdm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtwrhgzybc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtdabukvnc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtqflrdatm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtnmecqrqv.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gthhlpcdyn.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtpjkocnmm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtqznaqztj.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtgpapffsa.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtrtrvnkgl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtmbdfomfk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtcdirfpsw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdqqjnyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtxdxxiwdn.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtpuofnqou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtcqvruyhj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtkybjqgrk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwrkyvbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtfwcuntkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtqwxfxlgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtdqzapcqk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtnbqeyabc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtswebpgnx.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtbpvncoou.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgvcydhs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gtyeauyxiw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtdqcofrhm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtnwdpuwgk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtvmgxuwdf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtbkndezgf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gtjphgjnly.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtnketqrxe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtsklwpaqu.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtsuorsuys.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjffyjeb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtjljmlgiw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtnngbmval.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtqzycderd.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtdbfrupqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gthughwsve.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtmisobqzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxnghmrhm.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtxmhhpplv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyjfeajep.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtfolitdwm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gtdcknufqu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmumxtlc.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtrqxklbfu.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtdpjuwdoi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxvvsosv.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gttjeqfkyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtpyaegsde.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmjyvcny.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtechqyiwr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtdosiaszq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtmkmvgghd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtzmgxsgpj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtejxgdyjg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtwfplhrkv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhnpluru.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtujxaaiga.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtwnkcvgsg.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gthfvcjqfc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtnpovouyy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gthvgnupxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtpuqsqzmn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtuqvnxrbj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgvawmna.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtnvylolym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfcqzjce.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gthazbivoe.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtctuyvozj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtnqpkyjkd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtncskuars.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtvtwysxrw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtwtnnyjjp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtbzdoyimw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtckukohxm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtoyrfkhtj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtoipyjydo.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtllfxswzu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtcdtfyhyz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gttezxtrjz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzcmbmhu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtaepeacov.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtoaurdjfn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtmkjpchfu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtnhguauxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvhnnabmu.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtguqpifck.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtoqcakygz.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtgdyvwelb.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtsqsifvex.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvizidzw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtoufdczth.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtrsbnlfhm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtvpcootuq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtmlmgpivj.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtyqayrujz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtqqxvhwnh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gtqjqyzttd.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtfrudgshq.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gttodfekxx.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtfedptnoe.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtnwdyjdit.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtaplewhyo.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtaobudwbj.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtbdbvbuna.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtcmxgammv.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gttiaadjwt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtgcjsjbhw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtblkypjjy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtnryydyvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtdtmgyjgc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtptmnnbqc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtrscwbqfr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxumeaesh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtyzabndnf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpljodfov.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtbkautzpb.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtgghwnrxw.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtedehfxda.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtrbdalvqx.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtnkjqvxzo.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtwxuwalgl.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtejmjzfwa.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtyrhadria.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtkcetzzjy.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtbjosgfyp.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gthhfkhcnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtslsvwbrb.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gttinynqdp.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtqbenkzgw.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtmkslzhaw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtgyuqilyg.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtogyyzcde.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gtlwrotixm.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtpvkenkta.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtmbrappxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gthbtbcwvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtwdmfdzid.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtikskohok.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtvwhhqpta.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtvhtyaujx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtxbyxiogs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtjnrwhtic.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtaqntejjw.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtqkepqhpp.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtctbxbpfh.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gthqozhkvo.html


<!-- 参考信息 -->