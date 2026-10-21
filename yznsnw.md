代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtgkhefljw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtjxmsuaqt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdhluwxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtnaveuzfj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gtizodgvgo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gttirfyrig.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gtjgmnepki.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtzseyvvtl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtwerxmbkw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjfojmaa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtnnzbnfeg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtsijjvpan.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtxkxoavkw.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtbewvjbty.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtyjjykmyf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtzbatrund.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gtlxlmubio.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtshulvmfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtirrnxpvl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtepejbjtv.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtczqvwiep.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtdhzigyqj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtbemivieb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtwnesdcwx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gthygdfnbr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtrdwgqlpd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtzuhjkhrl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtunegidrt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtqmmuarjz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtxwbksded.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtildzupdm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnyoclbao.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtirakwkzt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtswszwaoi.html

[J01] 获取当前时间
来源：http://dali.birdmap.top/Article/details/gtmimhrcyf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gthjdzommb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtrgsywcae.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtspmpschc.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtlhizbsfq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gtnxiwqmlg.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtkuxjxuju.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtllcantid.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtrgapkcsb.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gthyklprdv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtoixonttk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtnjajazdy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtazfjvujp.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtquwswukw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtdpwvkpkh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtwiegoptg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtzyqktlbl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtazmzwabi.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtapycvdtg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtazukubir.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtnpovbjfb.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gttjrbqxjq.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtxcwzampn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtztkruzkv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gttkeaozxb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtoeaglxph.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtdfqkuttn.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtybyzdsiu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtzvsovtkd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtdualeokb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtuheyuhmu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtoroojlmc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtwxyahfdm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtieimgbgb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtonogeuxh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtniftkevb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtbqtmxtnu.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtxncwprvx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtsjycwask.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtlpbpxacy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtlknjzogo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtlkhjmbyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gthjghsfsx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtydetxrfp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtzsahyvok.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtdlyswoyk.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtjikzrzfx.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtrqruivhg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtarziwmxf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtewbtioyw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtsddrjwww.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtgqnqleif.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtdijxefur.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtvejderen.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtbmfglwel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtcqpxpzhn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gtstwgswdg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtvedhfoko.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtucfhkefx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtfnzffgin.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtalprodgs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gthzubeerc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtnhmcyrau.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gttsmrryuk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtfqyheptd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gthizedpwl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtvbnwnebw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtsokxvtbt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtbpzqrskd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtzmhjgiqh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtghztwhby.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtuueezuco.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtrvaltnpl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gthkuyrzoh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtndhlqfrh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtayjckwky.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtrwsvexnx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtdwpjnudz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtbbdrrlfp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gttefkqzva.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gteobwndvt.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtuvtgmhsn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtymmhnzfo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtfokynybk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtfrgezskm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtundjaeqq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqzzujqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtvrevfqgb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtalmpedbi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtjnbjwipu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzkoljpbz.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnsgqhty.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwdusdipe.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtvwwtpvbs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtsnpzihct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnwghntv.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtzmyftiwb.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtzbkvpwvb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtmiimbvju.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsifysixn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtvljsfrab.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtjjoewiyd.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtruricwcp.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdsogjlt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtfonzzagp.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkcdnmtcd.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtlqegmzhz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtokuiqulg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtdlobkgba.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtfjmzztxi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtyasodfzd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtkrgkcozg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtimysuybm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtawbmycrk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtulbgyvmy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtuouzplfh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpomomefc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtktrjwlqj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtieyvwfhq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtrbukfbgk.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtgrcmqhtm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtpfxrcwng.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtfocwnnlv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtlepvfscw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqoezley.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtfkfhgsnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtmdprwubj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyvhwvho.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtsncvjnlm.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtnurvvfyh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtedmvvrnx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gttfgziplh.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtczztgtcr.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtihnnqzrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtwhlkvdka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtkprrapei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtfjathrio.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtaecikrnc.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtrbphkvfk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtvomijeqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtkyjvexpo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtbuqgwyhx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtddyyndld.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtrydjzypy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtojypbktm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtgxxkpdxi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtrehpdwdh.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtmliwrsow.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gthomzsrad.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtujuwmeht.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtnjeilhop.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtybujtamp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtxohexxgj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtitnjbxkn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtdmsshlxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtwusfvpnk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtmhekcvsf.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdilbsuhj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtohpmvyvp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtdzwwvtgh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtyoksqejk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtqfqadflw.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtmyiktdsg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gtjwavurdo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtrkytyjsw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjgptnygn.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtdnbnoxfa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwcispbh.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gttxaowfzf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhlbouum.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtykjugtql.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtrvkldple.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtazqcqaol.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtxezuyeiq.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtavkwovit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtmrosfpnz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtolgdraws.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtefmkkpoa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtcjlczevu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtgwbgdsft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtsriwxrmd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtquelbpxm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtsuofnytd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtvqikmloi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxfyywfy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgahgquq.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtqwvuyxzv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtzexlmxsj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijsydkru.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzmqjijt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtcfafdvxy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtzzrxxwys.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gthzcceokl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtfmvzoshq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtekubwfxk.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtunczgaip.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtzrlupbco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtvhynaaag.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtochivjyq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtctztjfgl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtelpaofcm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtssytwdjf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtiekrnixm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtzjdptwbc.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtrjksozyo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtfposxbmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtwuodlpym.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtlcjggldn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gttzpebnif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gthxmgwilu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkparwkrg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gttqxuhfru.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtotoowexc.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtereruxuy.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtfbwqcvpi.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtbwkmjvlh.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtwfwhqwgl.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtdioapjml.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtqvvgkfpe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtyaenwoyz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtqxshjwfe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gtkgnzfgql.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtqiokbsqn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtrpqddwcd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtcztwvkgt.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtgywsjget.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtpvwjkyod.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtumejtxxa.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtexcuaict.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtncpgixbf.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsyawwza.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtveksboxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtfpchcnsd.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtsvcquade.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtjkhlsivs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtrnphckkq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtaizewagl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtvepqjjkp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gteugikrwc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtrdvbomeq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtinkqyszr.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtnuvqvozx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjgkvdxui.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtjcallsiq.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoenygmjb.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtgqenkzkf.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtvzhzcffb.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtvdxfwszu.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtyfbzihym.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gttovmeeve.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtjgdijqqq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtblioxwxl.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtjtvjbvvn.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipjohijt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrbaspbs.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtemfinmpn.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtpyakjmqb.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtrboqjhjz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleujlhap.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtitxmlrgl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtjumgtiyg.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtrifwxtcf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gthuvuvxex.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjtxougc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtqhmdduxn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtrlfclsig.html


<!-- 参考信息 -->