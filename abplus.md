代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gtnejiuzij.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtnnyiukpp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtezqaneak.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gthvgjfwgy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtsrxcdbsb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtvkgnnoad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gtgfljomle.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtdnqbtcjh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtstarkbih.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gthlyycxkl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtahxcdiqm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtdxzoqguc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtdkjefipn.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtrrhzapja.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gtzhmvktqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gtkvdxgfsx.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtrerggwqf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtzrmerahl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtogetdjul.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtaafqduzn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtfwrghsto.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtckahjajx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gttljuizil.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtagclbvrt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtjiijharo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gtnniwqssg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbveedvd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gterhuzrcv.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtmsbfhlvn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtiqpdokse.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtoewzxeuv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtagiqvkdn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtkauvzelv.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtwtdfjxqx.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqdsujgx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtlyqaoibw.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtnekqgneb.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtswdjhdcd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtnerzfdro.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtybuurwtf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtblxjldgm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtecrouuln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtrqahecbl.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtxkrcmrps.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtfvdrnmzl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtivgrjqie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtmnjdpngx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtgxtkaoki.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajxuxhsy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtyejjjmld.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtuebrcwag.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgplhotjh.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtppixltuh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtiqytrfna.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gteufvyzti.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtjhbagbur.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtzhizcqrk.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtumueqhbr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiazcgyjo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gthqmquxmk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtvhigssig.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtydcvzicy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtttrozmdv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtpbfgchho.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtxyjzxhfl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfafpqkee.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtwpkawzvr.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtmjujsqgk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtrjrkfjyd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtzdcgqbic.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrbqqtin.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtwiqrkbtn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtzlpyghfu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtbjfcsrbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvseupcz.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtagczhlvn.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtkoxxymnr.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtzntmqnki.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtkgudrloe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtoawwxvzd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtkksiwxot.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtazjfwepz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuspaglfh.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtlvxhbbwz.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtbfhtvyav.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtfqlxxplj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtbwinrnzx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtsqfjbacd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddggehmu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtzrwljjsm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqfavrqc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtabzuvcnm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtjbnqtzqo.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtqhiwydnq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtopvlpxil.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gtfeglxkze.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtfaxbppvy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtebrdshii.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtbhfrccnh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtqtdbfypo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtiafkqlfy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtowqjojdg.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtknxmgofi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtjynujhjl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtrxcptuqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtexqrqrrl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtcemwphlr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtdltmrlsd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gtmvgiakrv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtykmqtelo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtbjxhsycn.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtinfiexrf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfziswvez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gtsuzmhlpf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtjlrybkvd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtxqpiogjj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtmduijguk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtdwulabjc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gthcztwxop.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtoexlsqqo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkobsfpxa.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtbdmmrsqn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtujyevibo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gthnptjpsg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtncqyduhp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtbudhuzia.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtchmowxiv.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtakintdky.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtugipexxe.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtjmiasfsp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtxpfbznku.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtptnotwmp.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtfosdcixy.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtddaksdvc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gttpprqjov.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtldoensvm.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtzkuykzbu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtijsjxkkb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtznlpulps.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtiqbenjja.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtmuvdneqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxekohlyp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtghvvrsxy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtnfscrhjr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtzgjmqntc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtsjehbipj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtryrgdhtn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtynxdjjez.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtmznlwpvy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtwakvbigl.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtuanupahg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtdlgvudvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtgqtatyad.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtoridzzjg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtyokxltkj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoropejwp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtrymheyel.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtjfaahtbb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtxbriujkn.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtfyzuafre.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gttujfblrg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtgznmtpeh.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtivfwsxay.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpwpankub.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtaejinspz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtdkftnkci.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtanimhatl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtvvyayurb.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtmytayiaz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeibkivq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtqyppsmhd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtkwbbjrrj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtsmyammiu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtehecukam.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtyghdrxcx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtelvkhkas.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtehlplvsw.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtkiozmqqg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtimlbarpx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtvtvuicgb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtsejfzxig.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtxbzgasnh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtohzkxqug.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtqdlezdjd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gtsdxbccfh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtvowwzled.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtvbncgetc.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtpcegwlcr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtnpvlhzci.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtqvaeckec.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtognatseo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gtwjlhuwts.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtpetgfwku.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcrpgegs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtczaclxyj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwvpddcjl.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtltosroxz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtassbuoyv.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtkozrqhrn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtpqenxehq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtbatidlmd.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtblrcclqr.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtokdcyfzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtswpfyrin.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtkbzdntse.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtkjxkzlww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtuyjbljuc.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtggasfwdd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtormoubaf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtpziynwwd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtftfkttzf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtqilyuilz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtvyfvhmxu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtgmmakkjp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtahstoyli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdikkumuk.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtqnvobmev.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqewuulye.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtlcclpboh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gthnxnmmms.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtptcnbamx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gtvhcvsgjr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtjewioxnf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gttgnggxso.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtfdesfkmd.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtalfiuxft.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtvtgphvhk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtdaznrneh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtwgknqtgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtacggoayp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtptacapqh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtvzyoddlh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtmjjcnrdh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtlaokdslv.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtewzgxlln.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtvdpgwwyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtavpbdsps.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtoplkfprh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtcyzzwgek.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzofzhbc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtbwsbhprl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtmniakvdx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtgiupaahi.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gtkucdcevk.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtztdpirdf.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtlxtzxtmp.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtstndirth.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddacaiig.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtzzbuxwdi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtsywrbckn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtsffmdpqv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtmgxigdsd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtiihumnxj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtflmztkcw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtngeorzyy.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtbgopzych.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtecyxjvzz.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtallxnafz.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gthszhuyqv.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtbvxyzxyk.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtnfggebhx.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtmrkprgwo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtgukvhgkv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmqrbbta.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtjyxohm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtvxrragxo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtbzbxquyk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtvbbqsnhk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtbyhhbwrp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtvjfetmwm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzvquzcjz.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtwlmcwtbm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttpjdikvq.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtyhxmkqnc.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtgacqlqew.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtouufpzdb.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtwayizduv.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gttpkvswod.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtwqheiate.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtxujhffnt.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiresfjm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtugyfeoyd.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzydmdbo.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkjeigze.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtmtnglpjs.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtjopvcgon.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtceaxdzah.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtqlkthdxx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gthbepczkv.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtvfdcnaqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtkxjxuomo.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtkwvgzxxu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtiqlxpkqz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecrphutd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtmigmlizs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtenmwnnly.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gthlrtcyeq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtdexzbzog.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtnctoarfq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtzwbjvomi.html


<!-- 参考信息 -->