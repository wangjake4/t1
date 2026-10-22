代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2zaoczktc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2ffnyvkgq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2hoxpqixa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2nrqslftm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2cruatgae.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2sfzkzxrr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2cjdtbzaw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2eaccwiew.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2yoczaasd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gt2bgqaurrq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2hljnetqu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2nsejwlow.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2sjkiksxg.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2kzncrkzk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2rgukkgin.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2xbuftxai.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywghvulb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2lpvwfkpq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2svcjzrpq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gt2gvfxabki.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2ojisdmlv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2aoxctjtb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlezzdwe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2pdcxsfol.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2dziboaay.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2uplksyxz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2nsxogsva.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zdbrmspy.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2ptbbnjqu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bowdafqq.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2zyvjzrxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gt2zsgipjlw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2fvtwrldb.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2refberpq.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2rpakhmvk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2hzrqvnvc.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2xpkjtehn.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2pvfrwlwq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gt2dbmltbho.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2mtdyxfxc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdlrnvds.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2eukbftvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfsevicr.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czwjhgva.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2azgjbrzn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzrszouv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2lciteaei.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwyhbwxo.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovybfmzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2qwmoddph.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gt2yhihfveh.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxxsvmwl.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2pijwgkjx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2tpthcpzi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2wapxtarm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2zolhrokk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2ifuvwpoh.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2icrrxirl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqmchokt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2qjldxvae.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2zwwxkrtl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2nvecfnga.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gt2ajuyangk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gt2hkvyhrde.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2fyrgtiia.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2yxslgqdg.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2llfghwwc.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2yevmfcex.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2tvnlvkkn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2vqrghsuj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdwwkdzy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gt2ecxepykr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2qkvygqai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gt2zrpsnxrr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2mshtizsg.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2jdjgpqep.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2hsqtylhp.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gt2hmaahutf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2cpehudub.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpdnmzyy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2dzqigkci.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2eufzkjwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gt2pdefjetf.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2afugdodq.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2nzisppgw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2oxjqlpsx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2qqpfjzgi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2ozhjbxvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2mnwvdhoy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ajkbhnbz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2drrygrxj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2goqtpjjz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2jymhdrhh.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2pnclqwkk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2dixjbhru.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gt2iduabfei.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2hnrfylwz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2chddlgyl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2vtmqgluh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfbuuaeq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2zaqpszac.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2qmmvfozn.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2utlbkolk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2gqeijfgo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqvbptcw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2dpxstlht.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2mearmqmc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2akduyhlc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2utbrajsk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2mongcvrw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2nygzhrbo.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2muecmdcq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2gsvgxdbw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2tscphmgk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2vrjvylgm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2uiomgput.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2rabpjdis.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2gxopgcpd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2cncqzddq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpcsfdxb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2aqekomkb.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2eoeweycy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rfcpgydq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gt2rufftbnf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2jwvpionw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmerwfil.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2zjwxxqao.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ujmdzjgx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2mxszvybj.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2netjtndb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2mkdztrvm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2omdaqvcc.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2pitdceoe.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gt2izjgjxer.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gt2fqpbazdf.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2iknhrolo.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2xkrqrmpq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2vfxipxxp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2jruqkhha.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2igygzgwl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2sjeqflyv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gt2folvbcyo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eglwidai.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2babfglur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2hdbpfqrx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2jwdgeacw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2nvgezejc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2etgaguvr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jydoarts.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2gsztolyd.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2oyxfndqj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2lwbnuyiw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2riuolcqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idflsjzl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2bsedgewp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2wonpbhty.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jussfbpc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvchexsv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2imhypawb.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vscckiql.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knqeazhw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2axeqgsmi.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2pbjrutup.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2neyyvqol.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqbsunvz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2updmomdx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gt2snkxxznk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewjgstbq.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gt2xntsqbub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2qxaqhhdy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gt2azubxpmr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2bhjvbdvd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2pdythosy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2vsbcfwsi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixkylssd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2ibxmilyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2lxnrijnk.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gt2libpajzt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2dbpndzhk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gt2duzehuau.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2mcizktri.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2bfojqdvp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gweoepbh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gt2zmwwrtzi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gt2omgfsylp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2qpypxwdz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gt2qjmidhig.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2jrexxqzt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gt2imahpfcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxkijlhv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2urrtzkew.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2mxikdhpx.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2fmenxdxt.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gt2xaizyvzu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2zfyirppf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gtljnvgr.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbvobzsc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vkbqgmph.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gt2rtmhvrok.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2cjumsvlr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gt2cpvdtdep.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2nrdjaosu.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2proufcmg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gt2grhtqduf.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2bqgkejcs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2bfygupta.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdmxsueu.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gt2ggleenfv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2bhjoqube.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gt2rauvczoy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2lcdspqyr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2mjugznch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnlwszhy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2yditlxxa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gt2tzhztlni.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thymaome.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gt2gaoasmek.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fggrcasi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2oxdfeskw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2rraljwal.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2xhwhvdee.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2wcthxscj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2jwndoteo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqalgapv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2cypaahor.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gt2khmhyywo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gt2qxvememr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbqzcqti.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2cwultkdf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2ehgmvpsp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2qkznajbg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2dxncarkx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2wnhqomda.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2idlzplcm.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gt2qxmnwjik.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2utxykubj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2takzccua.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2jkguayoe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcthoblw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2xugayiyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gt2gncrkskq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2hyrrzhil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2mttfnjci.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2qniwycon.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2zqerypov.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2jgjjjags.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxivqldi.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vihlykud.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2jiwpjpnh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2ysswmuur.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayooyibt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2patisxvx.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2jpwlkuni.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2svjlimij.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ithoskxk.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2inciqlbh.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2wxkuzkil.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixoiuvlw.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2fzmbkahp.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2zedudyjf.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2ccycdnnc.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gt2efskgtmn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2cymvsosh.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gt2xaquknej.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2gnjansle.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2dgyhjtfw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2gmgwmgsz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2uuvdablf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2iohmufne.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2xvwcjbps.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2pjyzivti.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2oxlfswuz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dtsfhvoc.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2mboalsrl.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2qwpzpbpl.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2zbetzfto.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2nuzhgtsb.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2mqnqprbm.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2yunaxrxk.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2eavzmvac.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gt2gnmvskho.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2gdcxkunz.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2rxegaexo.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2rotdebqg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2ezalwxyv.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2bexqvesl.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2cqeahnpw.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2ikkisxkj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2iqvhfnwk.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2vkflzbco.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmuppnny.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2viozvlvu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gt2yxspahbq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2dtxacchr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2iommvhwq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2mlzjybyi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gt2ktduqsgv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2ouvxehyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2gckwaxwu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2ndyachyi.html


<!-- 参考信息 -->