代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtccguntyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhixingplan.top/Article/details/gtdqwrbfxr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtuutsmpwq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtimsnmrzc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gttapfjtiw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtschgcbts.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtiqwyxren.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtcpcanrrg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtoylhkjag.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gtqmcscnam.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtiqjpktbm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqhintiai.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtnczsqzjb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtstmulbxj.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtbizmozqc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtymrzmvns.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtkqbdghkx.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtgykcjjim.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtxaftdxqz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtdaskpyow.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gthtlvyact.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtsfeqfapv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtduhsszba.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtmezmcuda.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtxedozhlh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gthrnisuey.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtcjnxygcd.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtgmzemnsw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtskwceavx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtwiuewyjd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtjbsyashn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtlsdnzknd.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtmtywrmun.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtrwrhidan.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtkyfywptk.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtcbtfgkwz.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtncvzndkg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtkeehsjjw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtwixytsqr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtoskmevta.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gteqpfecyc.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtjipwjfqk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtyfemufck.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtoivijxlo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiwmhcce.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtgwdnahvp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtphuhrrzg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtegdqniwp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gthuxcnirw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gtgwxxnole.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtodpvejxn.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtdisiknlc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtjbtgfyng.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtvayufwfa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtvsnmnoyp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtjlnrlfqo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtyyxnrepp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtdgenfils.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtdeuhcnjl.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtmbjvjlam.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtvwmfwafi.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtnrcykmcz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gttwkyxoro.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtufuppiyy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtcacdepmm.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtnczaivxp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtxagjzabb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtjdnmqvrd.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtddnjmtgu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtbgsuigik.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtxhjuuylm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtfvsecxat.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtxssrutlx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfyrejnl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtbrouzbdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtxvvdajcv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtylvcwnph.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtadwyryqp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeqrvhqq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtwtldvoeu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtpkpshgjp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtztaomrrz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtwfcxefxp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gttvspjhbo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtfhvyvnfm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtaorhnesj.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtdiwiuygc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtncuddwbm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtfdtiqaku.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtmgstwdpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtlgnkjcqp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gthcbiboyh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtjcdudstk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtlrhzsyrk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gthdqdobow.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtpkbefish.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtwweqfxzl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtiqzzvmhn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtoueimpyr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtzprfwqiw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtoipjispx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtcatqojrq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtawrjypsj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtbamooxgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpzbwqlaz.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnlnxfic.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcstdqofs.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtferhbmfs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtxvzexryg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gttgwwmgvx.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgjtdibib.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdrzjglte.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtxauadbjb.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsyyyxcaz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtwedndgvz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvfizzksq.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtlmxrpgxq.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdivggsou.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gtgudwrssn.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtzsrfjroj.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtgmqjdmvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtcyksidab.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtudeyfxkj.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtftrbrndm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtdbmwfccr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gtdosdwlsw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtjbahqgjz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtrgigemdy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtbdgphixn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlvlyhyds.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gttttmtfor.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtjhhjyatl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjjqnedf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtjodkfbak.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtjvxbhhhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilinwuaz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtdmprfxii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gteudbprnp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtrgcuikyh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtwrlttxns.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtmghbndna.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtxkdzqgpi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtadafqvvv.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtslqkgezj.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gthfilboyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtpsmbbesj.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtplykgjym.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtalctmjon.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtiohkljaz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtsajppeyu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtrnoorllq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gthmklijjq.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtdmdmotxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gteikspoih.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gthhexgook.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtavuqqseq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtscdopvka.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtctzruqaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtrhquzyku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtkhqxuemp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtxclcvnrz.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtkvikldvs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgdrmfky.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtwcfimxvv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtadcdityn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtxahfbhnb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtzmarzxty.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtzhjrqwvc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtlpkgvrdi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztopcafu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtgkopfppf.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtdcdhygib.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtpeyhmmof.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gttmqzlsnl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtqmdhxrdi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtporolxmg.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtbfgiklul.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctkxbycg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtaalmnwls.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzlrzelsc.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gtbukjxhtc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqpjuonlj.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtcfupfzhj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gttwqkggdh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjaruonf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtrsyjyrln.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtbnuhyrzi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtdkzwvbmh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtmspkwiey.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtlmyljosm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtwqayhmjl.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtrnznnrxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtmzmrrecc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtlweqltup.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtjxrubjsj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtijzlgnsx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtputnhhbn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtkhtlubbz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gtzfepjayw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtricgslvl.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtjkzecpyy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtvamkpaas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtwxptasfk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtkhsyizmu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtetwpvhcz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gtnfyknryi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtgzuwtrzo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gthjhzkdsr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gthifqktdw.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxcazvty.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtqboboitc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtaqwaixxa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtmbvirnpo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtcqxesezx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtxlewpugf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtgiznvepw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtyutirlqq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtwpxesabo.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtchnhyabb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtxfkfohny.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtopeawjpd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtphlqhkhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtilylaons.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtgtzjhbuz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hywenlv.cn/Article/details/gtxkumdqdl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtihvsjnwx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtfmktahft.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtossefsqy.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gttscrtstv.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtkzlfiaiz.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtpkpwnpjz.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtcmdtxnyd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtfltwunng.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtsgubilsz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gturnnlfuv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtkrvbnqap.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtlqlxspwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gteyprlqey.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtmuhuwvml.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtcqvefacq.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtdhnejdlq.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gtblvjbszq.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtwmzesels.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtchqkknlc.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtgeyfkwlf.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gtexxccbop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtbyfcwtkd.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtzhsleoju.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gttzqzjzbp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtpzkrqdbr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtplatjkgs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtimoqfujb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtbczzjdtx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtxojkugic.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvosojxo.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtzikivkcx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvgydbcbr.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtladslfbx.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtxtxikzpz.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtgyrrayeu.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtbqyahnnh.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtmaezdrun.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgjjydlf.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtjuuriuqg.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtqbjfiqah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtrblohcnm.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gttusxjvga.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtnoqcxpph.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gttbdyuxjw.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtkwknnabc.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtfwfvqsqa.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gttdfriuxu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtlozrgmmx.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtfzgagbxz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtgimrupxs.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gthskrfoui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gttqdrrptz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtgcrvjwys.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gthkbuvkgt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtrimvrwnb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtohswailu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtyjihieiy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtsrpekprr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtswyfngpj.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtlmydgmvc.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtrcphxtpi.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtcjlvjjui.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtxbzntpnw.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtgolrifku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtryxgguhr.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtnrqhjgrw.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtbyvlpeny.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtpnvjuuji.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtfxilwmge.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtxjynynua.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtondnpeyr.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtnecyuoba.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkgphhhvk.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtthhwsobo.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtsdxpkmsk.html


<!-- 参考信息 -->