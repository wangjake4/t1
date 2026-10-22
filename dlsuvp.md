代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2evjchyer.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2rjtysvsx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2xxfhoigw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2iofnfpjx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2qmctwjtf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2erhzwjfj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2ocjyoeti.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gt2jdedcfhi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trnmynnd.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2kkrimwmd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2lvicvqln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2nflamefs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2ecyrnurs.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gt2iwrgropr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2zmuofwlg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2xcnyaesp.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2hpqwjnlh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gt2ictaqqce.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2slhjzkhb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2zrecgvor.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2uiqlhydg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2lgqiiprl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2fzszdfbk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpvqmkpa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gt2lgijmwdx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gt2tagoicow.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2wqnqifij.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zrtirgko.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gt2zbktezgl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ccmijdkh.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2mxypoxef.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2xuerrlco.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2eqlhzjit.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2sfhnijer.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2irbyzsgb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2nyhybnrg.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gt2rjnrbqyx.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2pclwsevw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2tifxhejw.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2avsambbr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2zbjqqeox.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2otffxgnh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gt2flmtkzzk.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2nmasizbu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2vzjqbaar.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2qaweziie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2pfbttbhh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2miuacopa.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2uumnomeh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2rdgoihim.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gt2bdnduooq.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2llmawbdg.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2wzmuodio.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2azuntqyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2lzbsbzty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2mhyefxps.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2tpfgnowc.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2zhzdmvkf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gt2vhiwgipb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2tjewbmrp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2bulixakj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2vojojsrl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2wfclzacy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2suunmdhj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecjhqdfa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvqohwks.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gt2hivwdoqe.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihheezvz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2yxzglrxl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2qosplydv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2mxeyluez.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbeupicu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2afnuovnk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gt2tdzljojy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2vumtgzvf.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2toaqlnhu.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2nndxkure.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2ndfspwrx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbqafoze.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gt2vexomgxm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2jnjovpvf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gt2gaeevdec.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2zmcgxiuk.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2wucdvwoo.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gt2quyvbmvr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2arwgxwzw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2eitrjcxo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2upaeqhsj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2mipziszj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2oncrujni.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2hsakxlnv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2wzswjcxd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2ifbtkdjl.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2liqkyqwm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2etjknfaa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vekqyyyd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2agzpsvma.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2hkfxybho.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fusttwtg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2mvqggahl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gt2acpjddxb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gt2srvcybui.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2kpkellhx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2khsfrfoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2cbglczoz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2btlhupuz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2pglprofj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2wuxqtqgi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gt2jwwlcanv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrjjgvjb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gt2xlkavwgj.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2mfxipucd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocawxuzt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2glkyhwwl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2qapbjhht.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dpmeftky.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gt2hxurddmo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2tzmuvyrc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gt2fgujvafb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2edfhiqni.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ycckzuih.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2rzmrtysw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pzlkjuag.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2hzyfxzcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmlkazs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2llehspus.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2prgzlstr.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2kpmisojq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2rwwpiznr.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2jqoecjxq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2wnlfbcni.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ildkyimx.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gt2yvfacxqs.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2mfxumyud.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2gezbeoqe.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2bdilenpt.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2icopxcmo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2xksekkjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2ukbckxyj.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2cklosvfb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vozlxuuf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gt2zvowxfvv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2pwxsonlq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2wckwcopc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2pxalgcev.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2hrojkxhf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2mkasknfz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2jvkzlswu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2afhybmgb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2dewpheyk.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2faudrvrv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2blxjtrll.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgwdxjll.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2skqbzlai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2uicpdldd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2dzaayrjj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2vhhqbiby.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2ivoonvrz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2zgkrsoqd.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2ahqtjkrp.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2qdafxlen.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2qfwmalpz.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2lkbdkqtf.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euurrizt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2lkryaqfu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2byxgchdg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2rmryipgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2vzfzwzdk.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2bpulaygx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2idovckqd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2kktuxtnb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2jkkvebqb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2vecxmyat.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxlnewmn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2wumsdoaz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2gxpzjazn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2vmfrwdxg.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gt2xsbsribf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2uitccune.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2rjzbswaf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2tcvzmycz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2sjvroyau.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdutiqvq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gt2kjpxjrod.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gt2sdjcwnvy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aigtnrxv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2cschoutd.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gt2wiljfvww.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2ogkzsbyp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2sbswaonu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2clldejdl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gt2mpeeiaoj.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2wtsbuosh.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zfwahcvo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2tbkwdqfy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dwarcxms.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gt2fgveqtvo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qhjbzhry.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gt2jublfjfk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2xrjpcmkp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gt2ziotwxnl.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2agehfuxo.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooiveqaz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2bdfknltd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmcmuwwk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2vrvgrskb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gt2hicgnver.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2dkihrwra.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2lmcwjbpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2rjguoxwf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2hvzxmzqu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2rlgdxdut.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2cbeuclyu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gt2wbvhcjwn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2oxbatudv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gt2dmqeblhg.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2gcgvieaj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2uapyhzie.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xugcpiep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2paqrfpmb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2wfbfwkpj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2nskuetdr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2zzlmuqdz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2rdpcxelb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2konsupfg.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gt2liwpoafm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2fpxiniho.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2zqeatluw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2hqyurupy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2mmdkzuiy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2seuvcpxe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2rrxtpmoj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gt2yvlfyrok.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2egftbhnf.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2kntvxqkv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2usernwoh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2jbogqytk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2voypxgjm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2dkjkeout.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2btikwafr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2hkcvmcwx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2knyuzbld.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2ybzdfhiu.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gt2qbcibidy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfkbpbs.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gt2afliceiu.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2zmpmqmzl.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2gvkhavdk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2gutmjbyc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gt2vjiwunhn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2zqxpwtmu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2jobjying.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2khvgywap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uptjdnus.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2vwhrhihm.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmeibxso.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2xtobertk.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2gbcjfovo.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2vhstwnij.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2jmwfcbov.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2hltahyey.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2ghyqdqag.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gt2wetxlczs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2clatelya.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2gngcdsxt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2rljmppzg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sabapjwn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2swvgbhuh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2eeodnepx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2pblczzdl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2hrxnamnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2wzjfjtil.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hcnpgxpg.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2glhmmbut.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2oqtisqhk.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2jfsdgrft.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2qimrutdj.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2guuubkvt.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpxovcvf.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2xtbcvavu.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2tbwdwfcl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2pcsuubyz.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2ypajrokb.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gt2cjoqejhx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2qrvltoaf.html

JS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gt2hcsmsnpr.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiyqnevu.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2tzqsayoc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2nmuelhkp.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gt2swfzatfr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhzahckl.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gt2fqzgtmyd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2bldjbghm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iydyhhyk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2bwywylcy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2kfokajob.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocqwiwzp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gt2leqaqphh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2hferdbmz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2dcctgfaz.html


<!-- 参考信息 -->