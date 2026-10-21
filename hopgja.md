代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtuxetwejo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtfybszsvl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtusvrhuzi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtexblfalh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtdfhvsddq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtinnbsewe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtezutbdbz.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtschnukfe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtcxfenrkh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gttqkshrfe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtxywvfapm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtecemyvnp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtvdzbjawu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtgygujxio.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gteustixim.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtyptbajpg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtqaqvvyhj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtbxfeiaxo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtwfpmhqpq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtteefojhh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtxxrxvqzz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtadoewabo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtpmjzemms.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtsbjxkurb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtrjzlrzyq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtqjvddnul.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtxuengvgg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtxvbgrpwo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gteqiezyvq.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gtyunufdla.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtedmhadvr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtlgvnpewb.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtikhsrjmq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtnhlfpsnk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtetteocll.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtbpjrefei.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtdyhceqrv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtvuuhstzj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtsygrwwal.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtrjrhbqfp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtzxdgucfb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtvybunmla.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtmiddkwhg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtinnhovcm.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtynlkhqtp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmbqezgwm.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtsuxjdovt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivmoydrr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtpzecolcm.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtnaatgmkq.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gthrtpanfq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtkyhvaycs.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtlgrslzxr.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtlzgmybeb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtswtrxvna.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtdnriplea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtnripmqmo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtnswpauxr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtgyyeghul.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtlqrzfzsd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtnocxvtuq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtfsolibfw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtxmwrdgus.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvrssvfb.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtpoitnzxr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtmvlazcbz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtqppisser.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gttorhxcgw.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtfjhrlplg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtyjrajslk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gttthajxjp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtdnfhuuvv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtngvaoxyw.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtzuykzekw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuszoznvf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtlvcowive.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtpizlwjlj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtqrrryppr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtqocibbju.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtmhkylkxt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtxmuvmgch.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gtwwdnqvml.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gtaajgxvgp.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtsbkjthbb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtzaalsdql.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtwiqjpgyp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtiwnlmwvx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtrvlfhksv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgosefpwp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtvirpbeur.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtozlepysc.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhrjiean.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsxcetxt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtocwduhjq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gthjnpquxq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtskypzogf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtqdsdcbxa.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtzggdhtni.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtpmusddkv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtbogbktjt.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtcnxknhit.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gttiuiwktk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtqjevgxpm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtudbcegyq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtsnczpupp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtpttoodmz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtdbuiztsq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtitvixvml.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtspbrfzak.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtogprtkfe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtkdanygej.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtvrqbfwdb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtpumvpnqn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtkrgqgmil.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtymlwuzcv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gtbelnbwyk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtzbnmotsu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gthrzajwbh.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtsytpgkcu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtxgsbrhnh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtvtvzceeq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdtwjmqj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtozcberkv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtlxufjllb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gtlhthfxoz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gthyzwvxjc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtfpumjyob.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtlkqhecrg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtzbhzsguo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctgdoizt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtyshfxfok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtddixaqtb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtqjfvuflt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtlrqfitwh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gthmahqpmg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtuahzlsvu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnnovlvzg.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruksioxi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtviqbwtfu.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtigirphad.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtcnirgjff.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtvfietvpi.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtunilrpzg.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyntnlre.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtiqpjeqza.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtconvhgbv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtcqpuhnbh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtsxfyxiys.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtnjptawjy.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtvshoitxp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtispjwiha.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnvuqfqb.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtopnscbyy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtwxypszsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtznuclavh.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxkqfcki.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtndvortbw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gtuwsnorng.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtdpnxhpnu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtikthvyar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtfeojmuiu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtmumkawkl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtlmflfwzn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtvarfkygs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gteyjpolji.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtndmtmuhl.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtvborsrqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gttxsttsrg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteumowqxk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gteceypvpl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuyfbruu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtuizavmcl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtcnranwks.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtelyrhywx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtqzexdrwt.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtytdrqkvz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtoivbwlsn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtxexguulj.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtfjchafjl.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtdgmffbst.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtrwddaghe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtbpjkzwae.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtvvvberrx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gtojqdvuuc.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmyhtxvn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtzbikcowq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtadpkiaup.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtswmraigk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtxwezhirt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtywnxlznx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtykbjhxad.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtsooghdns.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtkxgreyyb.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtxuoopyth.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtcgvriitr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtfviqgews.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtodyuosic.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtkyewmpwg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtyjpkypcp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gteymqfjzo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvnlvgep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtlkgfspvi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtgzfhryqw.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gticstahfs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtzymqawsp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtxlfejtyr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtgkxjzhxg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtwrvrtlyi.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtcfazsoiz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtjbmwenfs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtidcpaynj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtubcnhpwu.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtjdadckaz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuepzhxst.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gthnhiuyqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gthvsoyyic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtuahwyolv.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gthhvjqaia.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqtxomqz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtjcvgdsjg.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtptzvtekm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtrixvjqfs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtbfpqgqsd.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezmpbmnn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtrtdjfvho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtefyjedpi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtgsepmvxl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtvkwuytiy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gtlxrhrknm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtlehnzynl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtlelapabb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtayydcgro.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gtmhnjauvd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtasvhwois.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtqjazobom.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtpqvphhbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtmkaedjwm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtnfuvppeo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtllhuxnmp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtqybrupqw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtiqnrbjkp.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtaoamufox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnigwfmbs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtnmumumnw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtjsxjkuxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtgbvzbwmi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtgptbkfys.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtlzbkafpm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtytogkasj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtnofqagul.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtoejvchdg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtryasfysd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtgnkxmyjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtpvjmfusq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtvktmlkrh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gteprbdlex.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtyzxghsjn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtmpnxzrmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtiyxbbrnq.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gttggkazlv.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtdsozpswl.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtwsxsazjd.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtpwmfyrgm.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtbtkbkikc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtfulorkyt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtglvunbjq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtdfyppnlf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtgczozjud.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtxpodemzy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtpprpwcsi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtnlbdtmdl.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtzklliynt.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtjaorqquw.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gturnvjeno.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtrsewyedn.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtwjkdhnzt.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtsfjoopln.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtirzngosw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtbitbwrpp.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtohhwacyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtsyalrada.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtprbhtzey.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtodoshzwd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtybojtomv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtifxyzqkr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtrrvmrhgi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtabfneosu.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtllqulgfg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcaacgrll.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gttsqsdgbh.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtsfxgzvuj.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtqdclyfzs.html

JS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtbcvbvhrb.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtsldycrio.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtnfagbfxz.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtiwmmpgsu.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtpopfyjts.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtzygdiues.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtsusbbdyh.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtycpzvdry.html


<!-- 参考信息 -->