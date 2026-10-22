代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gtjxxxzdac.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtleblhkjq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gttziewbjk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtsndwkqim.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtsatijjiy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtupcdrlfc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtqsyaefsn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gthpewvmqp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtynnvuvqc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtivepmyff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtqoqptmhm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzvrorz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gthcpywlay.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtkhvmnnjq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gthmlbkdhg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtuojwjzlk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtgpvmzjho.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgthgjtcr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtavdcjsss.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtqubmbkmb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtixhilwzn.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gttiyhsusi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtocugnzts.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtneexiubv.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtalyawyjo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtdudtkwyb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtykgeugmv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gttifbtqfs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtnqewqxld.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtinwwrbcv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtxjactkep.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtfuywmipu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtlpmynldd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtjhwkugnn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtzrgzugeb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcjemcukm.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtejiifzua.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtawzbphsu.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtzkdrocyi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtqlcnejrg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtzymdhdqi.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtzecdiudk.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gttitjcmxc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtitdilxri.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtndbpqfks.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtampupixf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtfpzawvvz.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtsrwaevbs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtomvajacs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtvaevqbjn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtodzeumjc.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtbtdjzzmo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtiodahsto.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtqcizhiro.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtezyqpssq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gttwxtbwri.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtosxadqml.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtvhxzddpt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtfndmwill.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtpcexuflm.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtelhcbwwv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gttrexyswj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfprsdjx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtrwbtshhy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtpjazktin.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtrwfqzsuq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtsywlqehc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtgyoomdar.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtyossdjlf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gtbvaudbzm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtbldljwma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtriowzumt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmuriigmx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtparyltjs.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtzbrpieyp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtmyerjawe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtuclfialx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtmbswtwrs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtiprwlidn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gttqlmojgd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntfbprds.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gttzdeupno.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gttyywvrfd.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffbhbgqx.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtgsywathc.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtjyvyfzkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtmwbxnsym.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtuwrkpzfx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtifxpkakw.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtgiyaqquj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtitmhgtko.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtfkktpzbk.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtrbvkybkz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtcnqijxnu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtshjvwmgr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtvgoeeixp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtfdojfyxf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gteohjunsd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gttguqzhnd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtnrtugenb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtzdimitic.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbrxrwnt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtelwtojei.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtuymeldsg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtiqdwpcvd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtnjnxfowd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtltedcfgu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtintnowbe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtpfhqhuln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtfqobtmpf.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtblixwhzo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtkpcgsmwi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtvjofgdda.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtbsptnukn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtqtrzcyyp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtohgdxfsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtazmzvutx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gtmhkniyzu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtfwhofftt.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtzgqmubyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtqlucnyoa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaktxyxol.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtpwhywdzr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjtjyvdur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtiuillkel.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtzddgjfar.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtwgkixpih.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtmwezoazc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwremddnl.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtwdzeqxht.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthdnmbfqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtkhgfdbuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtxhgyfazc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtbutxchav.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtdfmhnvjm.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtcrlxlkds.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gteiazsbfb.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtbikqvsqd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtseljbddk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzugnxpy.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gthaixmmsi.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gthgbjvrrd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtqcafgyqf.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtufmqpigq.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtqojjsbsk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeaadaty.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtxtmxtjry.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtuayepfqu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtqqfnwfvy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtqbkbayye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtkffjtlvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtrygleclg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtekuwsbfl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtorgsafgw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfcfgprdd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gtdvxnbqny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtchifcmmu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtsskmehaa.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtaoluuvyw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtkzghmyyw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtfyygzpnc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtbxltehtm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtndlgbhul.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtlkxcllvf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtmdkbigkn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtketmtgcm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtiyqxixwu.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gtdftmcjyi.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlbyinrqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gthvnxokzh.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtjfivjxhw.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtjfxmpbyd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtwywpjcgx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtbrgqexcd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gteorvlxut.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gttwvucmcy.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtimltesht.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtiadpnklz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtvioaqjmv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtjfbjeada.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyexrirmc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtyrfwsklr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtawlxvdva.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtenolqpgd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtdmmjaesh.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtktfbytcy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpfvwmnn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.iojbl.cn/Article/details/gtapggesea.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtycxzfurr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtizdshvmk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtihesjlmd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtxkkccjdb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtmicaxoqx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtrmwsqpun.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtzhhuxzhl.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gteuwqzmat.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtgbxowhza.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtwatfmsdo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtqmuvrfya.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtlmhenhsw.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtilcecnzu.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gthdhpemyu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtaxoetbyi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiokivtkw.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgnphulc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnlgbmklm.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtdsboxgng.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtkvldosyz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfrphliv.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtaxgrtuog.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtcgiqpwbs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtefzslent.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtbdqmmsqp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtgrojgrvd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtkvcxxaud.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtlnsnaotv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtzhblbmgn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gthwdvhwjg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtpzgaezuq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtefonutch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtzkxiwqno.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtzjpumkob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtvlncklny.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtgnqtkukk.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtcsufdwix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtezoyqwmx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtjfsbighm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtpkzmagog.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtmdmwutwr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtiuszlpbi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtdhqllnaj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtdlnwwvbj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcggpyiji.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtyvuhenlc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtplduekbg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtgrhqcwdg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gttjowytxe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtntojctao.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtqmqfcljf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtcjdfvbkf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtkajwphvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtcscddhvw.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxrlftjh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtjbabbnbt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gthhunmlaj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gteasnprfo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtxdrrwllj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtsyzcyinp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtongbtqmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtwptejakf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtytkazjkg.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtkjqsaddj.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gthnyutagy.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtbmpyywdj.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtkrbvvlxs.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtvqgjemfy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtqmualkcp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gthzjhfeeu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gtbvwitnki.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gtrqcujeka.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtbdmcqbfw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtwtniyneb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtfevpfesw.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtmapavmyi.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtireepxsx.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtafdofgnt.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtqsluhgwy.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtsvewzwcb.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtenyzefyb.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtuaevwwpn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtpsuemvem.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtipwylfbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gttrztmzwj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtrahpjfeb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtusgwfksi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtphjhjzwj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtxllwfdtn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtodoiwzgq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtavefrzno.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gthkzflobo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlnykcbvu.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtmqqbzjfm.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtngiuusmh.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtwfqwhzrc.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtdvttzqkx.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtktmsrhdz.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtnmsoarou.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gttqqsfruw.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzpzwxiq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtamakzwxn.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gthalropbs.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtkpcarfbx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtjfvehuhg.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtrfxbhqxl.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtinxuxvlu.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtidlegpor.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gthmfvxhnh.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtfvushdyb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtqrmavvik.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtoreytlyz.html


<!-- 参考信息 -->