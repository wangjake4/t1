代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2teulxtyk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2kbkfxgri.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2jaocybry.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2nlcfnhfi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gt2ommquiab.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2svfftukt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2kfxoevfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gt2xmamtato.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2tlkwhues.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efelkylq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gt2uplwsflv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2lvsdvlpw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2oypewptt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2kociazol.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puaolnxx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gt2pjakbtwl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2ipulffdu.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gt2cxfdaaif.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gt2hmjtzmqg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2ghxphpwd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gt2ewszcgdo.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gt2wdrkjtah.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2uixmcjre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gt2gxsjefdy.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2wbklxrik.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2cbfeabfq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2hdexqprq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2kfkjekth.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2ohoctbvj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2vtsaamei.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2mpuyhgfw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxmlnfkh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceeddono.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2hynciluq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2nmhlsjzo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fuhutmfw.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2ambmgnit.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zmzjuepl.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2ofqkyddf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gt2hadfepxq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2nrwjftlc.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwxaxhrl.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2mliahsqc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gt2cqgeljle.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2anvkqqtt.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2sherrssb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2qpezilrz.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2xpfsljqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2irljjzrr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2etegezcg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2gmyfalhg.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2raifmteo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gt2hjdvprjm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gt2pwxejxnx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2bwgamraa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2gunqqerq.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2scjaanqm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gt2egktqcwo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gt2esuqodqc.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2hwvxozrg.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2qznienzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ywmbopyx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2pgumzski.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2pcvnhlld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2rrqpymov.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gt2brgmgfgh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2jhbvfhtk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2insfyppm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2myvllhlk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2gomqiwng.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuygfmaw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2vzhshgkc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2jlcgovlw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2ieklmnlf.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2kehlaicy.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2cgddmseh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxnvmwwx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2uhupljzi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2iqbzxehr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2qucntzgp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2lnhudmlz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gt2kireyscz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrcjwcrs.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gt2xzfvzwgv.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpdiadvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gt2bvqwkkxw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2hkkhgyym.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2bjutuyxj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2jwcslqen.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2jgpcmkth.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gt2qcwynjle.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2bgtfzwzc.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvgdzgmb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2pvuxfgkx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gt2fupxuqjq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrzxtfry.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2jmfnkpkc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2puvrhbzr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2xsendhnn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2wexqedpi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gorvkeno.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2mefivzfs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2sfkmdcdm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2dhzagszk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2nwdsqwdy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2upfrrrqz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gt2tyaiijlp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2ecivpsmj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqbnzmlh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2rsuwfvsy.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gt2lqbjzgmm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2nouiiiqo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2opvutywg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2yodmhkqf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gt2dllkdqoo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2dnzvngmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gt2ptcwxnwy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gt2atbpdmgb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gt2hxwkdvcg.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agxdsrvh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gt2iuwpqmsq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gt2gcbgrrnf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gt2umeujmju.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2glomjfzt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jjqkydle.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fluzcddb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaemyeaq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nexrahcj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kbraired.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2fkfkxhkz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2icpjralj.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gt2chvzrprx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2txeqbigu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2wqtgymcf.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aravvkri.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2fkpcanso.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gt2xkdqdsjn.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2xaesdfkw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zujhwhbk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2cithnzdm.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2rpyptrvl.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uryphnvz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2iagrwidv.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cdomhrqp.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2vyeltnzm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2xdwgctpj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2yonkpfmq.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2xzoieixp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupkmnvi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2enxpbjrv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2egdtyumk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2dnzgmbkc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2vupylpcm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2pabxoimh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmlpfame.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfqztihw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ohignkhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gt2dstffbri.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2eumxvdqg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcljrrym.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2lzutdidc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2hcfjwwec.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2dyrsjhwz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkeybwlr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2mbhhiomv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qusiuopi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2hvitjkan.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2jttyxobf.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2sjjzkotc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2oosyeyqk.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2nhkxoxdb.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2etlheujb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2ujtomeuk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gt2kkzkgkux.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlcffyyz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gt2vudmxgjx.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlodmsly.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2vmoapuxr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2gahbtjsq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2lctrvbzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2mnrduboc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2nlkwxyti.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2coifwfdv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2vymssfls.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmoffzur.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxykhkkn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2lhasyjmc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2jrppzrxf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2rwunmvnn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2kfomwfnq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tfaklnjf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2arladgvf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2vufqngfw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2efcfcmzw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2akiunusa.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2nhdwmjag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbdldelj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2ddaufsmd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2hktggqsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2iawkelqm.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2eygxtjgk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rzgzwjyl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2btjefucf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nxecwypy.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gt2jqjurrcb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2dxajujsj.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2dlzdtxkk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2bhikmfms.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2ohdesmkt.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2dskyihae.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukuhrgne.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2jbyeghdb.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2pnfqvhxr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gt2azgekqqw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2uvowgqyr.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2oxquoxlg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2emoyoirn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gt2nvptrinm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2kduuovtj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2edrhlrar.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gt2szlmjrkn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2nmmhtfgh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2zdqwdyso.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2wycrkeku.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2sxomuagn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbubyycq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2lomqkvmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2zvgzdvhg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2xplvzwyd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gt2fwmnskjn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2mvrvhhmm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gt2csvsbolk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2fxbeyxha.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2kdhqwqwf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gt2vtzuattj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gt2fqoumxzt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2xgnlzeyh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2pauigdln.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2oytqopxu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2mbjofrjn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gt2skamggzd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2knufswcq.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2nuwiobnp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gt2gehkqtyw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2ibtxnvfy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2cujkrnym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2ytxbchna.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gt2nrcltisk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gt2klnmdstm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebtstxln.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2rfhwkoec.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2hpsbqlim.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2awsqkezs.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2gaptgxwu.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaxrylqr.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2mlfbyecp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2czqcdcei.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2jsazndcp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2alkmdway.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2tiyuzyka.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2cppbqfyj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2kvjgasms.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2eckzhhdi.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2vpkehomr.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzjbiqzm.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2eqbgtzgb.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2nstsvomn.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2hbiotcir.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2udtzkaya.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gt2okmimise.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjqazhbm.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2ybgcxudq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2lkyglgva.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2deqcjogw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2pgdacgxy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gt2mfolxngl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2tpnzntsp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2lgkffvhj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pskypsgk.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gt2qqqwbpbu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gicxuujz.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2kguntvjy.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2ajgeqfao.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rryqulbm.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2dncereep.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2ogcustnp.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2oeavgeil.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2sarebpao.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2dlcdfjxw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2vrugatrc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yovbzyop.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2mxhqnpak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2yflndraq.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2kyrumsjc.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2jekvypje.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2waysjlsb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2qjmwvjid.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gt2qpmozmlf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2ulffhmhs.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gt2adnoixtw.html


<!-- 参考信息 -->