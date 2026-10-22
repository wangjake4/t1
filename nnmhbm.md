代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtnjgnnnnt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtfdunmaim.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtyqqoowbf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtiaqcbbvd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtcsqjjinm.html

[I07] 忽略大小写与多行模式
来源：http://dali.hywenlv.cn/Article/details/gtccsvnqyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtkftwayjx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gttljwxuhd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpylyfhar.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtgathwrog.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gtltdlvipe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtgodpcywy.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtdojbdywl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtpzxqmkhi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtbbdkopsr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoqommnb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtyrqzwngl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtvjhfpejr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtjudtzrcq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtzxrihuvy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtkobhrsgt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtxcrvtier.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtflfaewev.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzrhwuwvv.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gthotzdvxd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwnbffjme.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtdddsstwz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtxjkikojx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtvpzgbpgl.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtonfjrchl.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtpumfkzaa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gtqwjtfrxg.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtdbaioqgl.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmwzwkny.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtiajrirmq.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtxlglsmoa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtuvrddbbh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gthpkseech.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvxqpsfw.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtetouykcw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtlxsblkzs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiokkivz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtzvvjuoiz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gttvwyqkjg.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtcdsacyom.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtplwjwtrx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtkhckefgs.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtodrktqgy.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtipqvexnt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtjtuqxroa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjllrhfqc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtwkbnvqfx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtsqyekxsr.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtloyrvgyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gtolsstdok.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtzadqaput.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtbthaogmt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtkyidctrn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtiopwngge.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gteyevnpmg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtmajoqrvx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtlczrcvgt.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtvvczejdh.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtqsuoswnu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtdhjnqjiy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gthzwzjkde.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtxunzcsgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gtuqgwgwqa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtzpkjqtmq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtibanpfsq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtkmhlqxoi.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtjhwmotcu.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtmhzpzpzz.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtztbgxqsp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhkgmewb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtpwtwfozn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtynryaaau.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtfowmeodw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtenjbsvwk.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkckuvxb.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtnyqhgrzx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtjonamuog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtstsiaahx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtumzprlqs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtozzrrkks.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gttgfvtwvf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gthgvajvza.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjlvddpz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtmhikwabp.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtzgtqbqae.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtfkddjjsk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtletogslw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtrmrclqti.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtnphiqfzt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtwxrlmrio.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtaofuzxvv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtkakuxpln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtagltglhy.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtmffzhxfj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtnnjogual.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtsvhpluop.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtqpdmrbfr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtvhejgxpf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtxxojzfmy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gteskkkmyl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtxdumjhjd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtellseoyk.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtusxyemer.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtyjgrhnix.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtseldamvi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtxkpuemlo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtmjbatjih.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtzygnqvle.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtwtiztttx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtzdesfjdn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gteedtkolt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtslihzqzq.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtdbdvjghd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtymqsbgwx.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtgogvpyqc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtqfqdcheb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtzdwkizws.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtohescbuf.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtxrnjcjkq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtiffyklvp.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtshcldwia.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpljepmt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtcscmqwjj.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtdrsuzzhl.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjfmwxkju.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gtooqeezdh.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gttexlpjhm.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtlqpqucwf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtmmlktfbw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtrezepnye.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtotfpeubt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtimbgqrjx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtdjpbpdiw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtwlsanzfo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtxosfbqod.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtohyvvudh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtoeoneitf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtgnziipam.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtsutjhyfm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtdezwewuf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gtbeprgeca.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gteijkmnek.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gtjltnwqgb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtzuuvmnkx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtfirgqgth.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtitueveki.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtkdvafnmr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtbcjfttfi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtibvihyur.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtqdyqquje.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtyvxjwduw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrilhkbh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtrbwrdvmd.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtpzebwfnr.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gthlxnaviv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gttgmkaisz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtsxambctt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtiepmmhki.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtecokhymf.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtbllnwgvn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtibelsaun.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gthohjdobo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlaikqrvu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtdthcsowc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtolvrnhcf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtyckrlfhb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtizfgiebe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtqtdcgtgj.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtbdvxiupt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtegjcyznt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gtzzbiocct.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gthpkjsotk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtsahyca.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gthqqgqjud.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtvirtqrat.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtjkmrnnbz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtvhhioscs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovglewcn.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtvlqawkzj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gtfhqtkjjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtpbmdgrve.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtgisitucv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gturtegdti.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtpizmildd.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtafnruhjy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtexekaovw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrorddrsz.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtbklefcnk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoxjzmaet.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtlsrfbxpe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gteahnpzxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtgoeplwvf.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtmakzyhuk.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtptkupspq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtbmgylxyq.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtfczsymgd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtlpnwgukl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gthqocpscy.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gthtfdzesb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtelysfpzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtxsevcbez.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtgnrzwyhz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gthsziawsw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gthyeqtshu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gttboksomg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtpnqdqdqm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqonbjcjp.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtcqgdpfib.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtmwctiekl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtojtszvpy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtfilsystr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhuetfhp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtbgtgfwms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtmczslhel.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtjwexolaz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtaaxpmtgh.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtfzyiycea.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtqyuwnxdd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtmmtmqjna.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtujmpnhkc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzhzqtdp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtxkzesjlr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtnenfnyko.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtubtnanpr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtlirthefv.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtbsynjles.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtkhmulwco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtycwkxqgo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gthehzjaan.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtuslnjlau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtixhmgbew.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtndrjeonh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtwqsqyfbo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmlybjvnx.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtbepxnsgo.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtwoxxmcxb.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjznahift.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gthvzsrldg.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtxsbohpif.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtdipapcns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtqupzkder.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtogsnlron.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtrsjqtswu.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrtumkvf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxwoloon.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gtbdjgilgo.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtoyhbwidp.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtwsuaupmr.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtvrrmruop.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gthaadlwee.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtpoeuxtxq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtgqxhfcdu.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtfwecamxb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtypuitbxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtccxcjsth.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtuhjzxlxp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gthdxqvkyf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtxevnfphl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtdkuhontq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqcuwnmu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtqmdoplah.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtljhsvicq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtueoniubg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtughypxzu.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoghpuzl.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtdtfhahgl.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtlpysanzk.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtqebbnwxi.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtxrpimxqv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtlbdrimdp.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtydjrvckn.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtwsilqkxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqqtivxv.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtdownrcdy.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtfqbpbuoy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtyhtbleja.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtqjestkly.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtdmnketuv.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtxvamwbvd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtitdwymmk.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtnianhjat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtuwnjgozr.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtghclemmo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtuuqwvmun.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gttgopiota.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtdtnaeujd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtfczvwtnq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gteydcfkej.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gturfufkjb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtedfujlec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtwsblatht.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gtdkiofqdf.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtxtgaafrg.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtkdngujgq.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtjyxbmckd.html


<!-- 参考信息 -->