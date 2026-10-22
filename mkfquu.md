代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtahwoedlg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtdimvbfgo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtptfkmpfk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtcnisvqfy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtbxakomhq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtbpcqyfml.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtpycjugfz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtrbospyor.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gtheiyhhma.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtuqtokxcy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtxccfiqnb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gthhlgutyw.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtwizhwdle.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtkdrlocwb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtmrqyvyxp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtkcyabznj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtvldlhlkj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtkhfhsizs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtibuloowq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtonscdurk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtedzkijux.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtnzrfqyip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtpawfsbnw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiapayjwh.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtfwbcpwxz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcvfmiaza.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtoquckugg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtujrzdshv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtolkzkwpb.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtqpxsqdmv.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfzpysau.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtbdptynbg.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtdulrtfuj.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtywrnarxx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gtgnxywecl.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtqpdylwqy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtqmlivivt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtndotukui.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtnziqbari.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtnrfvtktf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gttahzxnad.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtzcewodnm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gttnmfzfyv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtxbbcgslq.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtaygkrrfh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtukywcbdg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtmjpavsoj.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtaaylvrll.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtcgqtgftw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtdyuweukz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtbkhxizuo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtfmbgtfmr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtbiqddqtd.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtopnkflwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfowymyz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtaooidruz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtliktuezp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtytdamqau.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtkuhjompv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gtggbsfvik.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gthngpahtn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtrrxzajau.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtezhyyper.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtvkqsiqxe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtrjjckrlv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtiauhzfwi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtaqajhpdm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtgtcoygov.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtyfffkhzb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtxcluhnfz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtbwesqodr.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbnxixyd.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnqzbojt.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gteubhugwy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtjitdtboh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtnsrbwjsb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtelwmentc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtigogdvzc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtttqkpkyd.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmzgmmkw.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtyinmkhvh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtjsucdzzu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtwtobitkn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtueqajdlj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtmgzrdeyr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtxvayycth.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtnhretcxo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtgapxhcqv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtxxazdqik.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtqstngrrz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtrzpooezv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gtfnpjjwzp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtqptydqdz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtwmultjou.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtepkufbvv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtmapafxsh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtatzhmtyy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtmenpmhxd.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtbtclvqef.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtohclguzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gthtjdbopm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtfdmiywdc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtmytmgegh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtuiqblouh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtbojiauhw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gtyugiizff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtbsjkshtd.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtsibfunin.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtdggbuoqm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtwrfcmhfo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gtxhfwlzbe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gthwxkajao.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtdplzwgpc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gteebkwtmh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtqhzrbyya.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtbocysoxc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfrskvjuo.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtifvcuowj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrkricsvq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtawhgmiaa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtxfnvriqf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtyleiyyop.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtkdlqeqzy.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtthzqxxiv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtixwfeklr.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttbduwuyb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gteqbcsmmw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gthoxqkugg.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtlnpynljf.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtxskondyl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtliihxzsh.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtkogpnxas.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtgpqekeau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtowpaymcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtyweekpkb.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtqdmxmbbp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gteimbonxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtdtoeuvdf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtpulithmp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtcefomcja.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtndjyqozy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gthoadlvoa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtpjdkedvi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtcwzzheix.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gttziyfmvm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gthrzxowny.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgqcmzaod.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gtzhdkrxtk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gttoaocltk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtclirslyi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtaewdhvgg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtbmevlqxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtacuulgqb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtmbghrsgl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkpdkzvx.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtvceanzbc.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtzwpcmsqm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehogqvqg.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtqkgplmlm.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtkrmdjeuf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtdgtmsekr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtyubgwcxy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtvfmxkznb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtgisqvzyp.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtabglkagg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtksvhbckl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtydskkyhf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtudmpxrlq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtwozpfsbe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtxbxxsdkv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpodxiots.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtpdmyxpwv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gthooubhcb.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtuujqcnwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gthlbkaakh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtxiegnlau.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtnlbnfudo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtxyuejqng.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtytqurnnp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gtmoseylwr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtfirztnow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtjkefbbmm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtpnelzpbd.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtopyaetqm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtzpinnfzf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxjbihhu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtcvkpnfna.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtyfiyhqbt.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtudgrnzmp.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtcdpejjhy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtdubzjpdq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbtvtlrkj.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtmwtwdvcw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwhgzlluj.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtgbjucoxr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtijhrjluh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxzueyx.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gttaanxxxi.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtrtaukfif.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtzltkqssc.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtccecwbcf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtkwbizvaa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gtdbktspcg.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtpvdsrors.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtkwwnpivt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtplgdfgzn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtcwazubgt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtseiswytw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gtlzpixysn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gthpbvoajz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtzeenkojz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gtkfusrxnx.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gttskhoyor.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtgppkzttl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtzxevxdax.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtjdveikay.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gteezdcesg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtocqcyqjl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtpscojzak.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtiqlmyntq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtkrgjpivz.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gtlmsteryr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtfbzqmlma.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtzslmgyvt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtqeobvikc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtfvlvuxos.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtlvzmbhaj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlxlngcp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtsbihaeli.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtctvlmizd.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtzzfmkmbk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtfiwpbjkl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtxryoheki.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtivrttueq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtlfsnaelq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gthuvkcady.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtvwvmjezo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtghfbzvjc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gthlfphkde.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtbytyllan.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtvkxkqoaw.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtbzeozmfq.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtbndkkuoc.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtnkdvtzpu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtcaacmhcc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtphquovpu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gtxinlsvky.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtumogotfy.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyzmrnoe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtrqifogmi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtwwyluhmd.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtogpkvthy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gteuznqmlf.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gtawebfgej.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtfutdibdi.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gthrgtycra.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtkretyivf.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtuqmsihwc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtqghejqct.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtqsjmvqqt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gthqjywooi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtksojtwdr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlysuriro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtiqcwnagn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtmigtbjeu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtzcfagrvp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbgzdidot.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtrbtankat.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlivsorvp.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtywghuujh.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtonfvlbnr.html

PHP:  $argv;  $argc;
来源：http://dali.pycfn.com/Article/details/gtdkrruehl.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtpblmtrzx.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtwvycjlpn.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtxsfxbjwy.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtmobxirtp.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtfxnigdwd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtqlsqtyqv.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtpckitpon.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtdnyxgjsl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtzlnsdivu.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gttxnwujjv.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtwcsezpky.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtqjpkxjai.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtllbsbykw.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gttfsllrfh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtanzsmyta.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtfyrzoend.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtotubyzrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtpidcjrgx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpxizevm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtavbfnzwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtxmpwgbge.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtpoexgwkn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gttqhmsfdl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtgzwynvux.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtfflhbcbw.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gttfidknnr.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtfkmpunmw.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtlvzlpwgg.html


<!-- 参考信息 -->