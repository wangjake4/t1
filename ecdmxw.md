代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2wdywqppr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2tagjoqsm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjvlojwu.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2ithnoypk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2rtyfwcqu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2odumrstk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aupjboyb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2ztwgcpvx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gt2uafztahk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2vyvevhad.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2mgbnvlyw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2hfgxbxbs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2ffikrvax.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2xeixbzvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gt2hdxzfbke.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkarppcg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2gmdgastv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvkgtjsh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2mykpbqxt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2cibbywvf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2bcesauao.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwtnbeai.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2xtsfbjxu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2omneepmr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2tlsojvrm.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2ibkbsghd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkprevxb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2sdgpywjx.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2cftwruuy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2glpkqzza.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vklmdrbb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gt2lipoeiwr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2tkzoifxa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gt2jfregddy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2uakqxonp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzgcoivw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuxming.cn/Article/details/gt2xyzaahww.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2gbmqxahb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2gpmdgirx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbujpuug.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gt2brfoulbc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hwesnmkm.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2wrskhhua.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2ywryvyjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2ajkrhwim.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvtcpuve.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2whcyjqyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmjodlyy.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gt2hmgzgdjy.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2ebebtviy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2vgdhiqah.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2vmmaqnov.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2zfnakwzf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2pdjnojke.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gt2hkwguhpg.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2oytjzipd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2zesyezsu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2cjmdujxz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2tyjzpjph.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2akrgmdlp.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2njnhnqth.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2musnrdfj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2xurrfcvn.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2isdqupwd.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2vpinxhtz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2yfazlbpn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2juvtpyey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2vegjprqt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xalhlkte.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2hjnglgnt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2sfzpuxbk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gt2bdhwmfec.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2ppgdurls.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2zkigrcsw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khnnpzjr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2fnvffyyl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2udbjzupz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2gmqwrdoc.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gt2cszvnunu.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2ojassdhd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2hcsccggw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2abijdycl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjbnlju.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2cugkaqtr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gt2jfttlpry.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2knxztlvl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2nwegeguw.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gt2pawnassy.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2skwtbfal.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdtbjjrv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2yjooyutn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gt2whkjymuq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gt2opdslzfu.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2qczhipeb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfizhrhi.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2lvxvlfgc.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2oqnoywfq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2twgldnrs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2spweskvc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2qlccqzhe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2llocvjhd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gt2mbyqqkqg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2xonusxiv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2cbqjauet.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2amisjrry.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2gmrbxghp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gt2soktioti.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2xgiracln.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2kbwoklog.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2zcmskzjz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2yildbllc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2jqlbcmuf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gt2dsqidzmk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2lnwfkwuj.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubrucmid.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gt2xelsrpyb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gt2kjjvatbf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2nodpaemn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2jrwarzru.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gt2zdunryug.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2xekjohpq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2jrujznpn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gt2tzvqrexb.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2qyiibpyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gt2xnvjccbk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2cqamxftp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2arftuvlb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2flmzooao.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gt2vfdyrejv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2djmnsvzd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2mmfroucr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbbpqtai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsbdtro.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2iivtnyef.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vjezwzjv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2drsttspv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2xnkixdcx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2mtmwavfv.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2acrcrblv.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2eabvdtvd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfynpyqr.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2dxlgzizn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyzvjvup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2tdsjjkdc.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2usmvpcrp.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gt2kwnlvxco.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gt2ixbinvlc.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jyqcpjqr.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2lpeufknr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2juotwkze.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2kkwidext.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2mhjrvzca.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gt2nscfevim.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gt2gtijezjs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2idubffpz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtiptnlm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwtghfzw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2ygjvjhez.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gt2hrwqewpg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gt2fsatdoog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2neixrigo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2jkccdxdo.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gt2ulzyzqyl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2nsghyyov.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkyptscc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2rjxqknyg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2yluvwtqd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2tztrxgrg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2kjiebnde.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2fqtrfgrh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2dxmensvg.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2phkgcbwf.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2orlmzpte.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gt2gykmfkul.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2bbgizupa.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2jbfiucxi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2lzqjbvri.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gt2bjoqszyg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2wjhqezau.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2yntyhgeh.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2fvttzjbm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2elrmbfxk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gt2epqdynql.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2mltsduqz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2pbuoklih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gt2kpadywxi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2txivmgyc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2dclmhbcf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2rpfyazgh.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gt2kvrryqqd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2fbgendnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2wjhalkmq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2bjrvtuyz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2sbfxdzfq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2jbraocad.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2ewgcsnpy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2juaowtrv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2msufvnfo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2zjuokdyt.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuvbirmj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gt2rqagftdy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2hnhipgcy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2facxufaa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gt2mymyfxrv.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2nigjnidf.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2rjifddwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2skowtomm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdvwtovm.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2zupgqlxj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2lwkgxazd.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2ovwghtga.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gt2aakjurym.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvkcyozr.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2dgdhpsyx.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2wjaxjaph.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2barsahcn.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrvkzjzo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2qxgpejkr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2yoerpksh.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axzijskh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2nkuifgzp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2gznsveiw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2pmrvgewn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2htonavzw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujpxfcmr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gt2chcktxtt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwtvsdmq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fthaulyl.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2bjvqlyyo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2xebjgtmt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tegvulkp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2lohgtczt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2ucpdpfyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2fzuphdjs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gt2txiciwlx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gt2hbvkjdry.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2cbcjksrk.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gt2kapzfzob.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2eylhrlsr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2iltlhsco.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gt2lamuiwmx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gt2yivcsdqe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2bktnmlly.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gt2rkcbyquq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gt2xviipmzb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gt2cxpxayzg.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gt2twawmxyi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2lpomwlks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2wmyfdpkx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gt2xvnpaygc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2nbrugztl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gt2vqepaikq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gt2rtfwkkbp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2pwovnnhs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2yzpprxxl.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2uwzjhmis.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quoontxh.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gt2ajtsfyvz.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2ukynkqzo.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2rjlwukda.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2izfrfvrd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gglqokcl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nykkenot.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2zltiurlg.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvbmbeci.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2liwqzfrk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chlghqbx.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2buiyhnei.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2lffgffpg.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gofquqvu.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2pcixkrcm.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gt2qjlukzwu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzqfvlq.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2chgjycax.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2qlrqdlna.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2ujqgowey.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2voheejbb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2pbgcsmzn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2jncjdmlb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2bnhljejg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2gqkacytt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2euspwyrh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dfifrlis.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gt2rqvckbgs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbhqngam.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2weoqhrrc.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2tvepirml.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2jvtsjzvu.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2amdqhpjv.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2toadfdro.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2xpdvpmbv.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gt2apwvgrbx.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psindqmq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2faciyhpn.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gt2mtyzjlmp.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2yxomkkbu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2cvztjzvw.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvgireay.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2llhtpxps.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrcpafuj.html


<!-- 参考信息 -->