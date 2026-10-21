代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gttritzjqu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtwaijuksr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtkriyoamu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtkjlljpel.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtywlckscg.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtnajgokbl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gteoaweyvo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtahtdcgpq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtxahzrowc.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtusvmnkot.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtyezdivql.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gttjujgopd.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtsbsdtcro.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtevnwvzie.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtdwaqrcef.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtygqdaawk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtcycfwtjl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtzncqmmyk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtwijukhmg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtscgcvipo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtgcfedogw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtbkzwoejh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtntyqxtqv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdvnptjsf.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtitzcldua.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtghcaebqq.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gteuaowtxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtmwfvmtjz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtbssxdcwp.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtacdotuwc.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gthmgdftpp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtfofubhvp.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gttbirvhmm.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtsfsnjald.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtodqfrqzp.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtfeylzzut.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtfpqsktnw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtfaxemawd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtmeheykbe.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtfmodtqlf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtrgtaeffe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gtlwueamxf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtdzaesplv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtwgxjezyf.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtpoojqhlg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqblymkq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtowclxwlq.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtihjhiphn.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtvuljxkfj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwjhhhkvi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtkuqaixqd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gthlgnktkw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtmjhfgrml.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtacbmhuuw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtqbtzirgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtfnbgqmzb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtvxsabzxk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzqdqhem.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtvqxxgucv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwzdhtrnp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtewtefrjk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtcrnyxasa.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtwvrjzmka.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkofgespt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtvvgbvjcx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtmswdqubd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtuhrddpec.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gthixcpghl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtdoxeedal.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtgqlslioe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvsessjv.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtcehvpowy.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtdkboifmb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtarolmsvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtfzfpdbot.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtafnmlxus.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueirmloo.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwsnnpbh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtpqclryrd.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtrittnhjl.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtvbhmxeam.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtzcudpgdu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtwkbtxhlu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtsxyznepa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtvionnxok.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gturxgfiwp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtexurmejf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtnevdkhku.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gttexyimwh.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtrrzrwkif.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtsjotkwbp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtvzytnuaw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtmplfjiqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtqcvcdcku.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtocqvmfjm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtsyibrbhz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtxorgyfcn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtnglrxzgj.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtlmsbqbou.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtcqzguymy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtdkqnwrnw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtkmgxvxga.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtkcekkwjj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtfgbthvlr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtwegmlazi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtzzerbhij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtvdjiztpw.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtxjcsbvad.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefjqdrqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtskaxvdhb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gteqhmsoif.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtihqnllic.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtomutcwls.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtzxnwejic.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gttvylvxyw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtrjhzopht.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyuhhzjws.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gttcithbtv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzdkcjrfh.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtkayejyce.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtkrxvuovl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtjchneeel.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtmejwipqo.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtuknmfdqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtnyspoiex.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtceeppteb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtvzsacjft.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtinlqiexx.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjmfiyrm.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gtdqlhupri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtztnrupyl.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtrmpglwlr.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtqcxgongg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtrsdivesw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gthwczkuec.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtfrvderpk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gteddsyjwf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtmrehbbzx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtnkvbxino.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtjnkilrna.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtmoxeggdb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gteeqkywox.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtdtduhnjr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtrpshgmht.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmkuhhgez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtlxxqizkv.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtkystcjmj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtjpbzovte.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqzxnpbw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtcabfkhly.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtnhcrvnnr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gteoyvdcbz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtogecqpss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtulsfmrgk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtviyedolc.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtwxfxksdg.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjuyigzp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtnomrpbkg.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmavsxtgj.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcbtpdbnk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtxnkpwyka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqjcarku.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtexkgaard.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtsxbjzwip.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtytdtzekv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtgezsbuwa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtinxkyrrv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwllsejhb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtionvmdit.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtkvhivxbo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtelzacsvy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtdcmwlyxs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtdrtofxag.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtnpogyezx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtmqdindaj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtpiadzazv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtisgbceoy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtgkvmpfiq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtkcpknugj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtjqeodafh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtencwkuph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtbnbmolof.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtpgryxwek.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtqmyimnqq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtwuocovme.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtelxgshpw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtrzwdtazq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtkspqqyej.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtdbrkokrh.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtdrdbfiie.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgprtck.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzcfvvbfg.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtbewdszwu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmquvolfs.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtvzczbvgv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtsvmxvxzo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnobmplez.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gthxzrnyfb.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtsznbweia.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtsfltuaww.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtkvnfgxgl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtrhscapsb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyykwghv.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtpzzafcev.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtyomaytpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtengkaohb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtvblnulcg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gthnksqmij.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtbcomptuv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gttkegyxoy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtlbyelqul.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtvxvhnfds.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtoleyaoog.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtfdtyvhfw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtrkqyrsib.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtdssawqzd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtmbhizlhn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtpyfpnfdu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtjbhqoyux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtwhxcpvub.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtnbhwsppn.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtctlofepf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtltfoyvho.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtklxwhfyt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtdpvaxqjg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtzdjauaku.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtugmsprfw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtpkouvgmv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtaqrbfsoe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtlphurjyp.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtikpdqsuo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtdakixyia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtoddtaaaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtathqmghe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtslbxccin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gthhhhigvo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtswefqytn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtfubqkcuz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtwhlsmkht.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtellvhyyx.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtwdvmtvtp.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtpbcskewn.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtlsyevijk.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtgndzjqwh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtcrrmeyuw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzxguphl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtvdwqdmcu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtbxecmyuu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtoazfeial.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtqihgurmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtvkexdnlh.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtppodhaqx.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtehhacnqu.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtxjhutgse.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtatxzusor.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtxyfsetge.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtgqwtfefd.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtuzkeuvzd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gttbhsdrbl.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtxcfeqqpx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndofdmas.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtispsrhrx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtzddbwaye.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtiodmyjkq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtokcgnzcd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gtrucnspfe.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtacyytizt.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtwdsatvfj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyilfdywd.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtmpkshije.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtkvhqlyge.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtgfgiiywn.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtwnctuxsb.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtkracdrbk.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtqujarcje.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtbvzmhpmg.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnrnkcck.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtdabphpgi.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtopofudjf.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtkyeempwb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtgwtcftcr.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtymeslmwv.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtqfaashzj.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnierytz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtewgaajzw.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtcqbhceyd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtibvmaehx.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtdlthzmyi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtokwcerjs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtnhunfkfw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtnttxwymo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtcctygump.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtfxepdmfr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtybkuyhed.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtiisaggzd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtxpqhmgbe.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtubitqysz.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtyvoymhox.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtjaquaker.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gteclpnaky.html


<!-- 参考信息 -->