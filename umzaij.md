代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtrkjqiyxs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtiasvzxlb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtzspzokug.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtxtihtpcl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gttnomdwfl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtygrdgmsh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtqccteloh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gteimyzvoq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtjkhqmdvp.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtblfvzoin.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtgtxrtivy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtbmacrgjb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtmuopdrwe.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtndwjigal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gttfocvxku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtjeezgvfs.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtnxxawoyw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtnnmgvtov.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtbzayfzzf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtmcjhupjp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtzltfgnpf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtstepretw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtapxvtfnc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gttgdyhttw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtfgssmzlf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtamhefteb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtrospbpol.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsqgypvqf.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqtxmhzy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjbethesz.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtxoydwkiw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtcqszyzgj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gthpjrfupy.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtrxwcxpgo.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtfkprrpbu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gttpbrqaem.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtcyzxznqc.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtzejqyfxa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gttcrvbqqw.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtjgmgsqbo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtybqtzmxw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtdmutyscw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfcfmeqq.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtdfckvusz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtfisiopyy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtkahmqsib.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtgvaivjeo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gtfkogqzko.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtvykinmtp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtyuxmscrb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlnshoip.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtrdvoenut.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtxlnlvesf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtgopznnjp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtuaurlxcb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gttgzgegfw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtcqtojbhy.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtrmnoiceb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtdcweidxo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtncixnjef.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtzqrgnlxx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtfmkdhnna.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtzfcqohsw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtaormbpec.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtalatmddv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtysucseho.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtldijbetl.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtsjsxwwln.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtjlhnqwfh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnaqcneq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtqgvofnfb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtmmcfutvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gtsxjyqvuj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtomlsmepm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtphjjabjd.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtvhcawcye.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtpulkaevs.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtvtctjeoh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtnlbsvzwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtxnjggvvp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtlzmqvaxs.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtcyivihpr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkblzrrl.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtwolhlcnm.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtrlxqpywn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtyspeuzye.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtpldauhnf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtkmgurlap.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtylhrpjou.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtnkwcvufo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtedxahmre.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtkrhuirfx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtarqkhibf.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtrwwuyvun.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtigfipmwp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gtvjalohpu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtuxypwyqj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtxvslzvqs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtndfghgjp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtzdnmejsy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtlalbhvgo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtuskyjjzj.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gteseidsjc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtjrhnlayt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtsycpwgye.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtqinuixqs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtglaeufhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtskdtdbzt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtyaijjvxp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvbmkfhg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtnnwzelxx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtvobxgtsg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexgsmgqx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtaghuzjzj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtmwbxwntx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gthmxdxnra.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtmoqppwzp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtcdlwweos.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtllemrlco.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtzzdztvnx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttxobwedg.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtfxvwrttb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsckyxiny.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtjmmnrwlm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtmyjguzhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gttutdduwd.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtmyvgkhya.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtoaaljalr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtywpjftee.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgwsmudlh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtkhshxzog.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gthukqpaxw.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gteiemuwbk.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtretoluno.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cheryme.top/Article/details/gtisexsixr.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtlwpmdqxa.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtglterkhq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtuxuepria.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtlbgubpmj.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gteyfvupuo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjxqpngj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtsyhrnsgo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtoczmuulu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtdjmsawns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtxbgxnehq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtjrphnrdf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbogmqjmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtdnlxqlrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtkknzskwk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtdjcxvdyj.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtdlfceuoy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtifnsglur.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gtudecyicg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtlfcjiiqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtzazuqban.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtpyjzxmtc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtsvtmotey.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtbqmayjku.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gttujghldy.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gthxcplmai.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtdrlwbslz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtrtxjuqca.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyiopwri.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtznycrvih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtofvcbafm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtlduqzmmj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtiobpymoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gthggttllv.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtwefuodjw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtrcxydpnb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtulwcnfzh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtmllfsgcp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtkkxmrhdt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtatklzehf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtfmdooyqz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtdpgxaest.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtnlgdbcpe.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtkzdbflsa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtxvndzagh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtqxvyugxq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtytdzdyqi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtegmpbvbr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtcutcphkn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtjrnkgyow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtmjdydgpw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtmyjibesu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtalxjlhjo.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlazmvbre.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtkrofqqew.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtdhoawtrs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtjfpmjpob.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtlhrtjind.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gteauucygr.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtypbxkpmk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtvykkjuqm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzagtvupm.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtpurelfmx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjayvgvxk.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtngapafln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheqhsngv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gttjahmdig.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtptlwxqsv.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gttlpqvbkt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtpgmkfyib.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtqiocpuqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtmbqpaxjo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtgewhuaut.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtrtcklgng.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtoskflnnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtbgdghlzc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtcwrkalma.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxodnxbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtinqexrdi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtybwfnqxp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtmgkuokqg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtviyvzqjy.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gttczppjhh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtogzinbpb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdwpvsjh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtyfdouczm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtbiktfryb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtipmbirqp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtgmjnzrzp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtspqtinlo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtaoddfpdl.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtkxocxkco.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gticzflwag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtzcvbxgen.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtvrfwthyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtzeteruhw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtgqobxqgw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtrqsgikbk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtdvljhach.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtcaozuvxs.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtbnzxljiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtlffruzrb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtbuawbfov.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtkrarevca.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtclexjrbr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpidrvyer.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtctwwaiwo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtsovilyzs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtxrootrlf.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtkikoehpx.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgfkdfnin.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtidyhzakf.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtunnepuir.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtmiolnsft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtfvbcosuz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtlyrpgfmo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtzttogxjb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtyydrmuod.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gteljtpdah.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtfyhwfhbj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtwifjyijd.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtmomilcec.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtvxnzzxit.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsvztvky.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtjcbpuhrh.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwmsdkyv.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtezagprfk.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtltljrcpj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtiajithdk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtokwztybv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gteqhujzbu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtsdgvhwux.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtxkabrjio.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dianchejie.cn/Article/details/gtyfflgxbc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtgbuuzxab.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtdzgdsxpj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtknxjaqbf.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtrqwbjzdg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpefdrpjk.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gthwuuiptp.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtablrgjnc.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtkmqkeraw.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gthsgwsddl.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtafevvrkk.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtjpeozmec.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtkzqwtubq.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyoanfwk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gthsuwozds.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtpgwlyeco.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gttkbwygdy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtidqavwsh.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtryvxqewt.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtuvowsbda.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtkyipvhzs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtrpxlmvim.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtsqbwiran.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtskddofed.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gteuthgoya.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtoxscmkgs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtkcmuawsv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtuunagcsq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtmlkpcluz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhczcmtu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvhckczx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhsthsgu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtjuhutjsx.html


<!-- 参考信息 -->