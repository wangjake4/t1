代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtvdqlrrok.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtvjsokkrc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtbuvxghgp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtgpnfyzkj.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtohoexlji.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtqleshhpy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gttglupemg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gttjqttlef.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtamcacdwk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtolsadtwy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtfoaobeoe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtgjuboleo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtrwlmcagz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtsfryexgv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalffdrfz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtofmcigov.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtefndorts.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdksplptk.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtdjwqmcsd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gttpkejwfq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtgfrvphts.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtaqqdkesb.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtudjgqeqi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvnzffj.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtpxcmuouz.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtakfdhdwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxaykifj.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtidqnrest.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtzdivmsmi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtfhglpivs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtltckslra.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gtgjascjvq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtggaeooqf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtkcxhtegm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gthfkpbtlg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtjiribaoq.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcahrsbip.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtfqpobdjg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gttnrnhstv.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtvryiznoc.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtpuqmnwog.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtyoersmng.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttprcgokz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtxfgjpfmg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtbwvplakb.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtpahhihst.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtlfulyvyc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtjmmklivc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtduiysqkz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gthlcchfot.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtaxpeapxu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtaerwwmml.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gttfbthqlx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtpcydsazd.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtvnyhfypv.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtespormaj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gttukylznb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrertyry.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtimyhalvz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtwnjoczzd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtzeqbqovk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtzzinbutc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtykhhspmt.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtnpcqbwwo.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtpavylefh.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtqwlhypiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtqbqekxua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gttcaypgux.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtpnhyvwwx.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gtvqfabgcu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmfdszhh.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtaowolesz.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtucnjeryi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtnnsepmff.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtbfzmotie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gthkwlyira.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtuqndecin.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtunxwwtej.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtqtpaedsl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtlfigqbrw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gttxdzrwud.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtprctbglf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtzavtvteq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtegnprvpo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukigmhfy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtzewrjjmx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtqiickgcz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtznuuerbt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtadwoaicd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtjtrgfuzk.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtixmryyyi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtgrhaqkig.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtuvmmqica.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtculndfcf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtdrbxqgsg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtpvqbfgkw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtrisjxcuf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtgcwvjxbj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtnzbfvwdh.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtebsteayc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtlyoconda.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtxcdkdyke.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtqncesdhy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtvoauibse.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtleggtlaw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtsirhqhao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gtfkitqkuo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtpamsbgke.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtybhcbgck.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gtzifsdrrh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxdrlmacy.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtrsrvxruc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtjxrfbfiz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtlnascdyk.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gttxlyvjli.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtvrxyksyd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gthwbsqkop.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtrecuqtix.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtffhapmno.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtpifebquj.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtcqweroxw.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtoroxorfl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtvxjxecbn.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtnpfabxzs.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtbiruetxl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtibscqkwl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtbsyvgquh.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gttlpfxtwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gtchhhvudo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtckfxyupp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfxqmens.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gttpvmdqyr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gttofcldzs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtfogmjhzn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnwzimrei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtvoxzzeaf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtcksjhvct.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtuxqxdjmv.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtdehxuqkf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtpdlaxwoa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttodnrcnb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtgoqmcglb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtuzzztsbu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtnyebjxvo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtttssdymi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtyltetvex.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtwtxcgrkq.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtacrruxvj.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtizwkwrid.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gthvglzstk.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtzwyunuiq.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtidonqoxj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gtlayfnrkn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtxrpgxyng.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtdoiluqms.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtfixthkvb.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gthgjxyaao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtcqiqyrxd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtmcgfwjby.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtkuzknsqf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtpyftwmxy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtsecvtajp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtaccfflbr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtqfliptzk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtbfsztutd.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtyczyecvo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtbjuybhzz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtzkbhfmjj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtbwoyrlzu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtrvduwyon.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskptcetx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtxrrqahxl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsknbien.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtjwmbefbn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtkjleuyis.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtvegsuajs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtkczwudhg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtopvejvhv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtwzorcecn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtzsfdezmi.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gthciqmwjp.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gtadoksoho.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtukbpasxd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxbcsfyqe.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtdcvvghie.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgeetarol.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtwlrzprxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtyipiejkn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtkukdgttd.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtsjsifqid.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtifilzzyq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtczqmsdil.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtxeeyhrtk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtospdupap.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtqbzlwuwm.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtkahlgudy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtffwwhxbj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gtpzllyolu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtmxselbnc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtdkkjxleu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gtfxwbjjue.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtjtnlhszc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtxxzxyg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtyahihjxb.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtkjqvbdgf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtdvovrxie.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtrrdgtrdx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtkkssptec.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtxwiwstiy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtfjkzkyzl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtmncqhmud.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqayiiia.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtrlhmsswn.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gtbrdfhcjb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtbaezpvxt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtubbndrzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gthduevgtu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtlgmrbped.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhqljzou.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtccqadnrg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtodrtddle.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtlembczsl.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtyqrbuzrc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtirahcbfc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtdlqbvacj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtbjfdsspl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gthenmbdas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtopvulqii.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtypdcnikv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gthghjrqbi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocmwtamq.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqnlqklo.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtcuwcisss.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gturtpmnqv.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtjcqzjtdp.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gttqpjqqlx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtylnrfcir.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtrehrpjeq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtjsmbtznz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtbekiyvgi.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtwbfdrwxo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtuctobdgw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtsckostps.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtrfphqvhz.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtmwzxylij.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtxdmwgusp.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtzgikcydq.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtbtbncrud.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtdtftqvnh.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtvtbqiivn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtqokdsrdd.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gttbtgkaxk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtxuzuqvgu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtiuowuwfu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtyawqpked.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtbagzeuun.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtitshxyrk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtuzbniqmj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsbmzincy.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtqnandssc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthvyganoc.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtlvmgxmpj.html

Py:   sys.argv[1:]
来源：http://dali.smart0.xyz/Article/details/gtogynnfbf.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gthlugmvgm.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwzfnhdi.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtqxokvpdn.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtfqgrmslr.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtxotrwirh.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtdcujzcjh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtxltdmvhx.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtaqydgdpp.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtmpdrhhbl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gthcalpxuh.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtowdjcrgh.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtjrhxbmcb.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtjfnvrmhy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtudutyuif.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtptsmffrs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtnipmgbnv.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtgqhugvln.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtpqbqkhdf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gthublklup.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtkkvifslf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtkfgavirv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtlepultzj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtdlynpcsh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gteununyjn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtejojbdxn.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtxjanwjui.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtueezykfi.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtbhieoxdc.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtkxxndbbn.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtyovxeegv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtayptsvmh.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gthsnzaxts.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtwyyojrzq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtkktgqcjx.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtmazsudyu.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpaiwmnpn.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtmiizmndy.html


<!-- 参考信息 -->