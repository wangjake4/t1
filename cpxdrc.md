代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2lbefgiib.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2iravbmeg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2ajcmqjrg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2nneoganh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2hppfsqlr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2vpztfxmb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2iooporcu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2gayecasb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2oirqhkrs.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gt2lvujqwkg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2meqccmtc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2guokbaid.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gt2nkecydvm.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2virnnemk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2owqhaiyb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2vnedppvz.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2vylinegg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2ajijphns.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2plrhhckr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gt2vhelzezu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2mlofdtxf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2shxxvtho.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2zfpuexdy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2qgghukrj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2anabymvb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2linzcdfg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2cuqhadoo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2whpmeavu.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2gyarihwo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wzmqvnhw.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2didlfqly.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2capkmsxx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2cjnfjpjc.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2aguimuyu.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2sngrdkoc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2vckjtyik.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2ouhtaado.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2prvrgcxc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2cxnxqzik.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2rujyhsya.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2rgqentcd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2yommdfqt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2yopsclvd.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2hclciamq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2zcjbypol.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2orwxuawi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2oeidzrhs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gt2ggjwhfgp.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxisrzue.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmyygvrg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2maeozpuu.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2brfdahtw.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2ieswclvf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2jlgiwbfs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2jrzkcyjb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2corvqlmf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2nvddwshm.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2ooaxchse.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2aqylebdz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2lkqfiegf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2tcclzven.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tglntnqj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2npcgzxch.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2euhfdnlf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2wexozplg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2gxcygnws.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2sjrquclw.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2zevcmmpc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gt2mwgrydvw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2pejabuej.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2wbbseuqu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkacgqho.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2pqcelezk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2rllhmuui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2xskhcwcm.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2pccohmzy.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gt2qmtccwso.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2ccuwfptc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2hvaoxdwb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfcqfukv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2eiaznctn.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2wkonostb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2shuignup.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2wlqavivj.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2mbaliznq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2cgcbwafh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2ukxnulzr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajcirwri.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2bpolgkji.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhtrdvgk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2jyhhzkwq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2ikfnqdkx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2jftnwjck.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2ftsilbpe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2swjkqulc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2fzopuomq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2rccjrklj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2boqbvkug.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2qszdryzu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2iayjovju.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2gkvqxeeb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2yukhnqty.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gt2rjiacjwa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gt2zkrgffjc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gt2fkzsgdep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2notxwiob.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2xdddvkvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2hxjqilzx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2idlzinvq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2bihdwehw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2yfpwdkjd.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2pqolxuiz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2urlnmbfs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2linwrfjz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2ntbasxxj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2ugpsbyax.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gt2tgqnvkho.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2ruzncxbl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2bpteewit.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2msfmfkeq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cllcxmix.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dppxssxg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2uqmqumvq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gt2xssepths.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2bnqvubmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2bfobemvk.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2nnlawajg.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2vnkcsxgs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2joinguiu.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlcozugs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gt2nfhbazam.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2tkxzaxxp.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2zeiyjudw.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2oqicbplc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2ipkldtri.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2xzaawibs.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2iojmuzbb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2qcfmoibw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2rwdjlcbv.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2jyhlkhcw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2prtntojv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2bjvvkhyb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhvmaiyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hixudqog.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2ndvbksod.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2pskcchzl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2wnqyfpbe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcfdmwgh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2dkvadtsa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gt2ywusynwn.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2lmqgsxxp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2ugqaoyyz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2ddpikjam.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytbkorzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2nxoammxu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2efyzcgks.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2rzugpdlv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2pxfvosxx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2fwayqxsk.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2cittmxan.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnsemyrc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2waqubwqi.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxhhosqy.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2apzowmzt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gt2crcvcpzp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2imotvtzp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2ohyzdipz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2cgtsowzx.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2qgfxuivf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2lhufvmny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2qigofpra.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2bhdrtvyx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfzzljew.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2hmaktirv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2zzuosvcm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2unwmufbi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2gkgrbkxw.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gt2auahlqtb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2xdxbgawx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2iwlqkwmj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2muicyzmw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2nwdztwiy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kemydtxm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2ibosmmvt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgwqnmpd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2hvlyaxba.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gt2edyzgxro.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2qtetjwth.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gt2rgcsuneo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gt2kgsuwjbr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2dswjijid.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2kxnkfuhq.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2pjmmjzvu.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gt2wwqmkcpx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2wysumpzw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2phkyuxfd.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gt2pjcwuaan.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2memmorij.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gt2icdijqje.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2bwkzjpyz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gt2pgikxwsm.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2ttrahazi.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2svihsvbe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2axmfimio.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2mfyttkzn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gt2odzceypn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2ljtoqtvo.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2pdvlrbtg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2rljjhkyp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2nxuzcosp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2tdzbqode.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2pkccnfcv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2lavfzows.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdykprlr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2rmuvklxk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmcnuzeh.html

[L03] 设置自定义请求头
来源：http://dali.daria6918.cn/Article/details/gt2uedpjnns.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gt2hkuzesuc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2uzpjyzyw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2mxtswdno.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2yuamjoqk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2ieccpcpy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2mldzqthc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2rlthubzr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2qwglquea.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gt2povccflk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2sklixfka.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2qtgubmnz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2nhgxrepp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2cvfmjgka.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2xjckbjbp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2yywnecha.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlhuvaom.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2kmhdfbbx.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2yexkjado.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2rslzlckt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyuaujdh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2qeixkrew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2gcvglhmj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2puihrcwc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2qxodzpzl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2kihrhawl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qvadwbmi.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2nvgycqwi.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2cxjafipm.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2umoqhubl.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2ccorhazq.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2suekmlwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccavmcdg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2fmpfbmam.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2jkwaikth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gt2mzjhpccu.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2udetsdyq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gt2xtkssncs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2wyzagwgn.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2undwjfsh.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2bdwonryq.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2goicrdwd.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2yasdckhp.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gt2efyjaxkz.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2oylwuivh.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gt2iiklklzl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2zoxixakm.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gt2tjvsclnl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2wvvwsxwh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ngpxykae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snwtnryd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvygcpnu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2utljbpxk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfceosqs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2esvhaimu.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gt2zsctoqpz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bsxdrxkr.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2pudbumrw.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gt2ihjxosrw.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2owclgxkr.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2pegqvmhn.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2mtagnqzs.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2covqogwi.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2tdxeidqc.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2gjkaeymo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiqtgfqo.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfzuqmwu.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2uczviwqn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2veitydxb.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2qnlltgnp.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2ubkvvzbg.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2wazbnixa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2tgniaqln.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxstxvgv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2mjyattel.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2zgwkcfwq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2mlucvmxu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2dxfhfdzg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2jxanfpsn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2grfeskhj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xupyxzbd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2zkmiovlg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2zhcmxddz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2sxvkvmxh.html


<!-- 参考信息 -->