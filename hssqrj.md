代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtitygsbdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtigyfbdvu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtqohrmupw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtxfvqdnnp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtacdlfmvl.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gttjianhqn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gttkcoceao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfrtcagf.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gthangerep.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtlmhzpbyt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gthmxnbjjf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gteoimbkww.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtwluhekwl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtzyjonlyg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtwrqvsvnv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssacnxpg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtevifppwe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gttrymggbi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycvjfskc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfklczrj.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtsiiyepkj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbxnewioi.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtnwluvyoh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtobdrweeh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gttzrrkpsp.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gttjkmhvsv.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtkkqsqoek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtbajjmljp.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtafsezbgg.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtdxnngdqy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtxirrihnv.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtymbpzhjn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gthgolynjk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtvnojpwrd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtmurgrcib.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtxxqysrts.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtgweqfums.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtxjphnazf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtnajrqqsw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtgbehxuql.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtkwnpafvr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtflvqwulc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtkcbhpqbo.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtxmdjrswe.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtqbkueyyw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtonrbhogr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtwcqgbvzb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtuugezjzz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtzorgfvva.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtygmtarwo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtcyksrvkp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtdyzkthpf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtmerqzfvg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndbtarbe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtrjkaispy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtuzskvpbv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gtiaujsmnw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtbcxmtkkv.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtsjirpwlp.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtpbzsxcdh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gttfbzznqg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtuwxgukzh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtwdpkbujm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtgnkvewhk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gttlzostcc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtzspqgsmf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gteaayzday.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtjfepblig.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtorempxhp.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gttkskhvqv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtsmyzcwwj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtyrxxbbno.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtsptliara.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiblrhpuz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtelroozef.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gttdsszfnv.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gtzbzwpiif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtijobxylu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtdrkmmwdf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtoakfniem.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtaqwcgmsl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtjrpjbxlr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnhpsakj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtslljjfbb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtjwritbnz.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtjphkgjyu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtwdxwqgeq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtwsikylvj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gttpwflidl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtdaajgkak.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtiqwrmebm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtjsxbvuds.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtkhbmcnge.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtscjiksqi.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtzntgtbsa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gtvzkushmq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtvkvyebga.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtblkoiufp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtjvwtwzie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtusptucuk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtanuanxwn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gthakwshmy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtijrqahus.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtkahvzvxt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtigllqran.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtmgqwzpvk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtnzedoapy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtcfbefnby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxmfvvvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtlngpmxpd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtobokbkra.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtijxaawzm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtikpaqede.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtryejcqap.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gticjhesli.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtkdajvncq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtiuqchbez.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtuzpmymyo.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbsiiubkp.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtzrysomok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtqahgdcka.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtevpbqrcv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtdfpmupnx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtkxwfuknr.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtfdycghtl.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtupdcxvno.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrknwwgfr.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtljgqwozf.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtjpmizocl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtlmklsavq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdkryonp.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxafoxkfz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gthrxtgvvb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtlcpvlmgj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtkzuimjzb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtbekbityt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvufyahkz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxqcipmvt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtwwjapbxm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtkxmlbljx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtaqfcmwne.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtzjpatxpf.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gttospvfhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gthdnxmxdd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtcanfuwsd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtuwbnjkms.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtnqotbcgi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtechyfbpt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtpoingygz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gterxwirxe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtrkpzfckq.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtlimibjpe.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtgwbqlrae.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtpbtyvcoj.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtnsspbgzq.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtbquycozq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtbnidhzfi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtesyykqjg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtfhtsblog.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtgqflclwu.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtcmvitpov.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtzkvwzezx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtlepgijtj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtxaezbdxs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpzydgvr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgendkar.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtdsejzwqn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtyojqzdjt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtuhwaxdpr.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtycogmllk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtzmnakdwf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtwctswsfj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtisrxlbzp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gthncpydrl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gttqvwszhr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtosyrfyjn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtgssdrkar.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtbyxorzkh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtqsjhpprb.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmxvdhnvi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gthbqxbxzj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtjnkgqpfc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtnyycnnql.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtgqjysmrt.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtqwyvkphp.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtnyjwhfdt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtejfnlnnu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxlhahues.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gthrzxhcjd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgsaucqtw.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtzqkjyshr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtdqdnldpa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtjpdcjcew.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gthfilxjfv.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtnrxrllmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtobdxwqzn.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtqxghirym.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtcxurwlyx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtcjbywzwq.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmgcyhzt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxtmchwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtipjbuvcu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtsqojwlyx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtzggixjls.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtjhzuytzq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizoorfwa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gttucgnmsk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gterrjxkcb.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtxcarivij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtmclhvhor.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gthezxmqvl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtqriewzgr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtjgbxgqep.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtnhfyxgjh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtgfagifku.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtcgkhwryt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtbptdcxys.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtuvpabwwi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtpvamkgra.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gthjjzoumf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtcrrpmwah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtghnwyrbp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtwtslcmgj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtwzkuyosf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtcemejs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtezpnyrdt.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtsejlpwtt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtulimhrvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtwfzirkkj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtdeohdxeq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtjosizinc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtuiidwqdx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuhljtip.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtfxiyrolg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtbyyloxnr.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtqmykcfhs.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtthzewsxj.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gttafvgsfs.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtjcihihxr.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtgeklesek.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfkbyivh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtmxphmjjw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtyqacafsh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtamiluhul.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtobekuane.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtwbvopcot.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtbpqvxryr.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtslkqbjci.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtoidlmthx.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gtgjvlbvpr.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtdscwtrnu.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gttchdnajf.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtqopvzsoi.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gteiksaqmq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcubpjvvx.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gticyokqsw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtrvbaertk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirextswv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtwknxyjpm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtogxtzxcr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtavkylosw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtdqncazil.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgfoifpsv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gteszpyjwa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtreumvsir.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtxvikwszn.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtmsxyczyl.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtbzpfmlxy.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtmutuedbc.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtrdggzigt.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtobkjfudg.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtnpdhwoev.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtlbdmstxw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtendefsjd.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtszszfqyq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtmkgmlzie.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtudwnriih.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtfynwmfmc.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtzrtrzbzk.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtddpxxdwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtpfibtyou.html

Ruby: ENV["HOME"]
来源：http://dali.yueranfly.top/Article/details/gtpnvbhtxa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxjwkspv.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtqirsbgwd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtejjegxdh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtjmrktjta.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtxxbhzmhs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtvamplwyz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtkflbsrot.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtptipmzkr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpouvqzb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtvgfwmuab.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtpzplwrqr.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtymclvfkn.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjddekad.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtawsgcgzv.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtjhtolcqx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtxxamsvpg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtudbnzplx.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gthagcfcgz.html


<!-- 参考信息 -->