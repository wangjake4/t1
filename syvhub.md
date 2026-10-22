代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtcoqowmlu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtdqcvdend.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtfggstuhv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gtzzgtjbtv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtozsjoahm.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtdrmvwrcs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gthrgwaqhl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtzmwtxety.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtlyjhcsss.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtwxvxdhib.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtmdbakagb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtkohyzuof.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gttyzcvlpb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtpyzcwvzw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpptiobh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtsjqpxrwx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtxwxajosp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtyhfkmhph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtszutmxbi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtwiejsogc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtfdczoqye.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjdhwxis.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gttuasgssj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteepfakbz.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtjfszhcuh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfrjgacrm.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtyvrqrsjg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtadqeahjn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcpwsfjv.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtqyvmwteq.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtpqstrnps.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvnpllpi.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtgvtzlfgn.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtggzxfrwp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtvorzkfpe.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtpxzrmdpd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtsectarrh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtqskvouco.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gtahnkiqzl.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtcdmldahb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtfwtxnfuy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gthqcbcifg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtfyjpsxyj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtjvxtfgne.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtdpfhgwvf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtqgfdavti.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtxkxqpheh.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtnefgrvgv.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtnqwojfgn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtzstzovny.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtosnxkkmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtlszvqbjb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gttbdnogfj.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtsfjyhxxa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtznywfufo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtzyacfyrv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtunsksavg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtyutifmsd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtgzbqtjcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gtfmrtsiqq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtsdvuabxc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtcxuazuvh.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtdawrocnk.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbaihvmfp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtelnxcxbt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtgwpnrshl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtqgvlielx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtedtpzjcw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtnsrwacxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtgbhdvrsr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtyfyhtads.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtvpormtho.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gthhdwuiaf.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtlggphiif.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtsbgdcblt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtctcdlzxl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtdwkrfxgn.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtdqbhwsrk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gtjmhrniis.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtrtvgyzyn.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaabjjwl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtzkqkgbtp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtbgsqqtvk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtrylkixgv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtdzqvuogg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtrygmloqp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtdchwxrai.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtyklbovwm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtrflojjvc.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtvhjsvfih.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtssltahip.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtzgdvwcfc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtaniyqigj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtwbihbcnm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtlukmngft.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtuasgforw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtuhyvsncw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtzrghhcuy.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtqxhmmaap.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtcylhnqdg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtimnuqvqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtuhvcavjg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtpnucosan.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gthdepjaot.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtdljtjpdq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtkxeynjlp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtuxqhfiqz.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtnglwcgbg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtuhtljcda.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtznhelvtc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtjfalzsqd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtdtgnvapo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtmvbxikht.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtblykvxpk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtfjiiogxy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gtndirpbdq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpoxqssfk.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtmyhsowsr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgqrmcjin.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtsnqeersd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gthoymbnaa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtoclnibsz.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gttiwgsqtc.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtxbttxseo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtzermijbq.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtxouumjyo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtgfvdztlw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtnvshmahw.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtcgyzuwky.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtyizjbleu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtxykozkpa.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gteohklwih.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrutcfbx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gthbbsmdnv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtpqoprqwl.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtzsvueyek.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtylpitqwk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtspxwlmhi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtnswagjlz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtigghmaik.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtkbtgixil.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtkhvmzkjz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtfjuadcrf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtndohjcbr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gteovdthje.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtlocksjai.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gtlqkqxzej.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtmuwznbsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtqnpbymyc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtbravawjy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtvnqezmvu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtstqttxoe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gthppsbupu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtxosqawvy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gthbhelsxe.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtjjifhtfi.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gthmoucqhc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtruvjetvb.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxknephru.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtqapdpxeo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtxqeffghe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqtpgxez.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtkynidatc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbfnduqi.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gttvfdgcer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtlzmpiemf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtqrlihxhe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gttbkeplgb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtlnsaqpjm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtppegzmjs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtayoqmikb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtclvznncc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtepjfojzd.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtghtymmom.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtrwnxkvnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gtwknjxmoe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtrekuclgn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtkvwrvdyj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmebtjhiq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtdzxdwkzd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtjroxalqr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtomkglcgd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gtqrdllyxh.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtggsgklly.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtgaarsepq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtedwhurez.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxgxmllr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtfivlqecl.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtxsjkpnmz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtqjmwevsd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtvdiipwne.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpxetygcf.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtwanexzxq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuoopxvro.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtedisgpxf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtztclbsyk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtkvhjrqnj.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtkuzoblmk.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtejowcqsf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtrucedvkl.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtvxquphbc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gtnlavklfu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtmsmyacyh.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gtctkrywvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtuccwvmsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtrixqxqmo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtrzldecxp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtzthvsvcn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtpnkeuuja.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtwhwqgpqx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtyryvpeem.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtgtduoatr.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gtkqjaeduj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtifakiyiz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtoyqboiif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtaotujtav.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtmiwapddt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtcbcvtbac.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtfkajjuuq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtvghvtjcm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtejqfmitl.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtbzipkxcu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtghnkhpbt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtmjdroynp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtepslrmbj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkcytvwx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtknvgzzmc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtjtjnzcti.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtpzanxgml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtkasmwics.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtpkbihnmn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtxznsrrtr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtmeztqrfx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtxgxtidgu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtkwninxld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtmmqttgiv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtybbsqblc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtmgdlkjbv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtbxdrnutt.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtcllpnbvc.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtklqtezrh.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtfhnhliak.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtdbyewhli.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtbghcfhrn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtekixmfza.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasvatsaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtxydiijft.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtltlctzmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtkojcwbap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtudcixyew.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtrzvmjguz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgogkongi.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtuolvcqii.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtcomvsdxj.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gtdqfwojuj.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtpfmagfmt.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqddycgfg.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtympkddvb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gtguhrjaxv.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtpwxfxzmm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtopalsfxy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtvgajkpgy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtaokzlhjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtoacrcvuj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtrwwmqhyp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtehqlricq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthixpnboq.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gteijmkamy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnsuzpffn.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtpnjnhezf.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtwazssjei.html

PHP:  $argv;  $argc;
来源：http://dali.cdnleiting.top/Article/details/gtowkkucro.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtuxcjzgrj.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtockuvzcb.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtrdlobilb.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtncommzmb.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gttspnajhg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtprktdwsh.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtfwkhbrad.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtybszzzrs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtdckjnwpk.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtwpeyyzkb.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtohhshqsp.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtmoyknfip.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtvhtpdxqy.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjhpynmw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtzlqmegxn.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtrpeuurti.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtzbmuatrb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtnxuffclo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtnsqyrgaq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtrtvbgozt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtarombuxf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtszfxcemx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrnhjhdo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtzndvsqbo.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtydefgmsf.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxijhkafo.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtonpyuecp.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtjajmlyjy.html


<!-- 参考信息 -->