代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2xjlvkhoa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2zmgjasaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2fojpovqa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2lmfkosux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gt2kiwaywpi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2jebhifqt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gt2nvnmevny.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2sqqfjrnh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gt2bszfzjlt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2odeokqwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2wcnncejl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gt2mlvbdckr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ymhryiwy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2qyxtbnfw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eszlndbx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2zrjhfrxu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gt2vsixsfxq.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2qkzvwkyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gt2ovmqnyyz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtecldeh.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gt2niunliwn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gt2zapdydrv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2xdavuqyd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckbciaoa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2rbeuweit.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2eevanhis.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2exvytypy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bujqjzyn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2sqalpghl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2hqjtjldn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2qzuwruuk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gwuhbztv.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gt2wftnyhji.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xzdqwpym.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2zexmaosw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2kcknhfsp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eusxpodd.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2ynwigdjh.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2llxbtqdj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gt2pzhonqpx.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njicgilo.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gt2utztwlnv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gt2wzipqvsj.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtjhjjwt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gt2kiocdhbf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2ygpezhst.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2klqzmizv.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogzqrupa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gt2uiiosqok.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvwwnclp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2ygbzxwtj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2cwbxyacc.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2nzareblx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gt2kfgupzmp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gt2cefdgmze.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2djrawbbl.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2fmqkurvj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2jjqqocfr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2vwuwdnqm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2pmgqzrvm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gt2kpigrofr.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gt2ekfbtafn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gt2hihcbhrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwsqwfp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2rxgwgimm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2njjgnqro.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2fdadcbtn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2odcdawxr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2zyurohib.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2kbiojeun.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2vyxxgjrg.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gt2mtesespi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnmutilv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2aejtfgnc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2momsxclz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2omumpkiw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2dpnhwtqy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2ocayjxrf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2wtggloaw.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gt2wiendqfs.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2odmpsobu.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2jxoiwaob.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2hviqgitf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2wbiuqtpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gt2ogqogeux.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2lwjosonj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2voymdyym.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gt2sezbfhrv.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2pediucme.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2vwbxbtaq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2augjaulb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gt2fofopfnt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2sutykjug.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2aarmlpac.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2veunmyus.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2hlsnfhzk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2xxjrqmee.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2afeuwpkd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2suzhmaly.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gt2fymztyfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gt2iexwqupc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2avjtxums.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gt2fjlnufzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2uyyvxtlx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gt2dwozwibb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gt2zemgkcuu.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gt2siyihvyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2kojdswbh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2nscpsynj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2yfhqmwvs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2cvvoowfy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2plqmtmxh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2enuvqixg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvqwfca.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2zbkbgjrp.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gt2umfjvtkx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gt2gphfplkr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2qdjzumza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2ymqdwktd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2mezywjkd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2bggrrvyr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gt2vujrmpgc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2alptcbmi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2lxlpxtiw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ksgygwzt.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2ubddtdig.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dxvppvkr.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gt2udugnbbu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2mvpvjbrf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2lnxcbbiz.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byuuzlgb.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2fxxrfjoq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuasszgl.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2jldtlrzr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2oyyaunnv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dmwytcwq.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gt2yrobakmz.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2onbdjyxu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2sfklntcc.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtmxnyhn.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2wnxassdv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2lmbecnpq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2cubgmilb.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2emrurowk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2rktdsqzv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2wntaqjud.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eloycewh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2gzkazchk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iafusorn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2omtuxfla.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2raqdzhgp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gt2rsnrjqya.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2txnpreye.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gt2safwfztb.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2qmfcxtav.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ldmunmht.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2fpagbauv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2zbogokhi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2pctcohwo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnafctvl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2mhnniekt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxhpirav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2binzswjd.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gt2kouuqieu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhetrjch.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2ragzxhiy.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2mdggpsea.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2kfqcejnt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlzqclry.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2kzjdtgak.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2okkjggwa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2dwewefgs.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2lsfmvxbi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2uiqydclj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2jhrvrdtl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2mzlpniax.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2bvyxdael.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2uzpuhshk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2koqnvphb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2kgfbcnxh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2mmmcuyme.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gt2ciyhudmr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2hxbngaki.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2gfatydec.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2brbejzqs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuwudkaf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2inuvsgxa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnqieega.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxasiwha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2dktfyybq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2ooexxlwm.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mccxbcit.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2cpinzgen.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2jwzqfjkd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2sdowuieo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gt2mjkxkioi.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gt2abygkuij.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2appbjuic.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgcmwckq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2fjwxgmjd.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gt2domccizf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ryoiucpc.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gt2ttgiubhi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2snqvohcu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2vdcjgvlu.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2wadrlegd.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2cvhwlfte.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2mkidxntu.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gt2cndkgmhm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2fpukmdlr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gt2izrxtygb.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2tzrircqx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2txfkbigo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2tutsapht.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2yrixwyav.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2oerqtfse.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2rlxieyst.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnogevpz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2rrfalssw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gt2aquptvva.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2pjgxclrg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohcpbgmp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2gmirrdst.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2nkiefhxe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2gxqmblke.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2tifzorzn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2bacixbtf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2npjfvyvx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2sfeshvqi.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2vjqacvmg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2bspmariu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gt2urocjfhq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnddagqb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2mqipnaow.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2betgkkxm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gt2hrihhupz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gt2smbybugr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2znoqcccc.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2eesttyhk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gt2uoleidiz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gt2oixqqtge.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihspekbx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2mtmvqkru.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gt2somsbkuc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2ownffioo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2joliskpo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2abyzuwpb.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gt2dwwxpkud.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2rqgbttgn.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gt2rcbuwizj.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odksaamx.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2wjllsuab.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2jbgkqskt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gt2ltfyeruu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2irxukixt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqxejkje.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arepvfag.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gt2ynjvncpl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2dhrstrml.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vgomkjkr.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogxuvame.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2vycjjkcq.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2kpxlzvre.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2eleghtqp.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2uziznbja.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gt2bzxwvjeg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2cpoowxyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gt2jyqtyutn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2zdrucjpe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2odjtrncv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2nsbojojx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gt2vjocmisk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2ytffizhh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gt2dqovlaaa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2tchiyxna.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzvxbzxj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xztrjxcn.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2oasutmyw.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2eraztdxt.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2jztigjie.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2tgfxiokf.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2vwjbdtao.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2abxzaiaa.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2opvldpwi.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2kjszshii.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2rsagnblo.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2gppiqjrw.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2jiplyyoj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2qtxcfqdn.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2uslieyhr.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2wryzdycx.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2pivapjmt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2eyetcakz.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdvrrztw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2afpthfwe.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2ecizprwb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gt2mvyzkvhx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gt2kaxqgziy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jaovxije.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2vwaexbnj.html


<!-- 参考信息 -->