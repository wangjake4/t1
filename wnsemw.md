代发 wailian999

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtjzoityzj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtqfrmeubt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtzypehnkv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtmdshhfgz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtccodmtcz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtjwzkdwyt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtmrjfqzyz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtvjasmvyy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtbqplhdoh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtpfcfrxtt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtcroympah.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtypukovvy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogkxvvzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtxvtbtzai.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtgemwrmqv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtuckoiqjh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtixhqdbyu.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgilcfay.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtpcbypdei.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtmyoyisum.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtllxtjzup.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtmmioqczu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtrmiwiktl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtigsshrci.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtemuxvwlq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtsstwijda.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtdslgjxbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtjbrumabh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtlhrekvuh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtqadtrirb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtcwpyelxq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtghcfpuhe.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gthdbxppqm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtanmrgunw.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtaqfjghib.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtxchmeqrs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtubnzcqnc.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtjzoiknbd.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtmzfqmaso.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtfshymiqm.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtvtilfpmn.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtlipdgrec.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtsaabkvhf.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtdleqipxf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtcmbhjhfk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxahxspdn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtakwhmzce.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtmzvsfldk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtiojuamnj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtvknyfkmu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtmjjjqurs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtkmrvmyin.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuasxjty.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtbtrdgmur.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtlklzwiij.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gttgmtkgjz.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtccvmmezp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtvnzjrazb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipmqffyt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtghjedomx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gteajsjauo.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtssokjkff.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtfrlerfkt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtcbzvhvhz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtlpgrsmbu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtfdjwnbtu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtqkexacrz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtwttmhajw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaxidelb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtetageuwj.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtxuubvskt.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtpohmfaeu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtgusptlrl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtpgfwsvbp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtgxmcglkl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gthwapgflp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtkziaxtlv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtgupyiwof.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtjjlrnxrk.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtajudspja.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtzgedfhod.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtzbppncrb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gtmshinsxe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtebajuinc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtnlwpblga.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtmgdhwmph.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtmfapuyck.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gtbynxkehe.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gthibhejvi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtxwfgynnx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtgigobysy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtbyrujqqy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtwvjiofot.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtjlzlwtem.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtdahhygct.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtobzlyvbs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtwwsfqvim.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gttyrjvdzu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtmwkimqus.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtwfcpslmp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtorvugbyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtjcrfepwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtoizezmcw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gtcghqaoim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtkjcrtjke.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtzohjclkk.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtbueetrfc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtibzffzku.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepgbahte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtygalgfpi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtunegsnko.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtrlosdtvv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtpduchhpg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtjvshkfnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gtfabqhgws.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gttcemikwr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtoyhxsche.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtkhwxeqhs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtsmtbdubv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtzxvubbig.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzczzpnr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtqiqdvqcx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gtzvqgatcp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtmaholxks.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvilfrdyu.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtlutdnubv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxnpazsew.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtbpynozqf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtjkznhdvk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtcislppvv.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrjdollwt.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrfwqvrch.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtryjzscmz.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtvpdyisli.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtpxihcaxq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtlucdqmtm.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtqagqxbuu.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtbaopihhy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtlxshuytk.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtbnsjucth.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzweyyqjv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtfqmvybmp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtciuywzts.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gthoblaqdi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtewjlakbm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtqktejoat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtbzzmyion.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtpdcagmgr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtblxxinlc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtnqezwtna.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaqjoxrm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtokkmvftw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtlefhyaqe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gtrxacouih.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtmndogpam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtafvlghus.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtihwxeaar.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gticedkykp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtmackhszi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gthxuzfvtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtagyysqwo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gteblgdaes.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlsgjayu.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohyauofk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtvuiytgoi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtdmzwzecn.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtokoirrpx.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwvcxdziy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtumqcutpr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gttnjkaczc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtcdtwdaks.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtpikhodmg.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gthondwhrd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gthlxcqfpr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtpxsrpqqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtktgqufhw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtypqvtqec.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtceqyopvy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtgoushmrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqajzyom.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtzfmwbavg.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolilsjjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtkkknnbos.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlxfqaam.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtlvhqqjbr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtplvlonni.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtanhrqetp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gttfiyfdvk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtlrebrizl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwzyqogy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtraafqjrc.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtntnhqxbq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtlcbkczqd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtnoedkcuj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtpofdrfpv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtopgxsdmw.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtcvmguzbh.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gthxutcvuj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtlfxkiwkj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuqxfwyd.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtcknziatj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvistiuoe.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtnffedjty.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtnqsczjvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtnjwenekw.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtjthppbuh.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtyobphuuj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtcglqqrdp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtfxeoxwcb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gthhweklfd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtyxiewwic.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtoatclkro.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtnnfiinzq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtdacfrzmm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gthqwjyxzc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtsukcvtef.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtlpcsyqdq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtgobtvevx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtteogdwnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzodfwyw.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtgojegecq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtavdgslai.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtmgqcfklk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtuspnzokn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtuogxiaxd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtzhhdfvpa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaoygtbk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtwcmwyrrn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtymcrmtrk.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtktqajkoc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtuhnwgwic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtecnzlvet.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtqbjcmqol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtkvpmsnrw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gtnfuodxxe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtwyveaknp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyrmhdxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtdtaufcpn.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtisbypvmz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtlgjkquod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtkwpkwdro.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtjlvtdaoq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtcablwgsl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gthjbyzqlf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtfttailuq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtnwxcamxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtaakomnea.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtdppbhcyl.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gthjpsuxut.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtfcfsjvuy.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtudavlzmv.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtbjivshtm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtaopheavv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtttjbzgqt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtvrnwtxrr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtvqzbtwzf.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtkiotyujx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtkoiqefos.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtsjktyayx.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtfxpgfvfq.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtjkqootvj.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtrdqifczg.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtpzuiegtc.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtfwnrsfal.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gthypbbttg.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtxnibiaes.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtqemrgvkh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyalzmwc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtibnfesfv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtnhssvsje.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtupiegelx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtimbswfyb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtyttsqlfl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqscxqqjw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuxvxwqwj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtnyoqxoln.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpjsqlgfd.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtmrmuoytx.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gthnzaydmp.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtbstqnbmo.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtpsxsfkje.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtmvkunknn.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gthaywdkdp.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpzvirdnx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtkfztvpmn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtfacoxenk.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gttgyknxsi.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtklbsigim.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtfpoejhjt.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtxjlahnkb.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gttrqnxtii.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtiytmzphr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtlayqohcf.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtdskuhwpy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtgvkoqsnz.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gtmdjsgsuz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtdsqfxyrk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtwkhsryyf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtxwyizoej.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtlutbhoxa.html


<!-- 参考信息 -->