代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtfqsbmbri.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gtstdphvmc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtnchlygqn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtxrzitrod.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtduxrmpzq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtmiexppjc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtsmhirupu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gthzvjgujp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtkzorvdop.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtxmrumsgw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtrxsxsbwt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjlplkqrp.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltapekam.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgndxtbxf.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtdqwrrzug.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtpembmjpq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtgflrytym.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gthfowrthp.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gthzxvptoz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtagylnlln.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gttliayqpb.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtppwmtjpt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtqpuefand.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtizylbamc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtuhdsukhy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtpqqekkzb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtcefbcrgt.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtmajdgvob.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtohpjujrd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtqofvngpn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtuoqzsevd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimbokokf.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtwmqiqlrp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gtospyrykb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtgcsbywdd.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtcswtllio.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxksorczs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gthqmsiicp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gthnpwfyje.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtpkyfdbnk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtxnaplgzb.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtjdabfipr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtpjdywyyo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtsflyinon.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gtdhftydyj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtjfcvwnwt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtrvrdsden.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtjsypgfnf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtqenpybjl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtcnkhbzqy.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtedwcbmkg.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtpxdntvke.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtvbqwssuj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtqgvruocz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtorcpxgeh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkbsfmwd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gttnzzpsyl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gthlqdsbba.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtghlcweud.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtxydidumk.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtoolrmbow.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtqdohkdnm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtjdzmpazs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtdxnhhswl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtbieryawz.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtzckgpwmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtovmxvvsk.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtgrlntuob.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gttndhhjoj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtvuilltfh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtwiwlfcff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtxnbtvxvh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtdkcsptza.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtzsjywrug.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtrrugsxib.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejytkszu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gteedfbcsk.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtydnwqgxq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtfgzqumgm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtiyqdpbhh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtqeqwrbkz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtrxzcyayq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtbkazimew.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtsourhqvl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtkwqphwmk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gteexfiqqo.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gttrnzlgwq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtedecywoc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtgfqkeucd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtghazkmjj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtwtcbhzgm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtrnennayv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gtbziwseva.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtcgkgvvga.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtfgodlioh.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtozljuzyj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtpilirelz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtlkhqpgfg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtdpvntbtn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gteacinyls.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtiftgeuau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gteuvogypu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtimlufqtp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtpmxgfpip.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthzvyfzvs.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gttutryjtn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttldkqass.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtkmcsuemm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtfynfzzws.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtoazfkngz.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtepqocphd.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtftzcvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtqlsgfona.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtmncoqwpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gtykmbbqvx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpemqqfbt.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtislgfjbl.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtfkregelj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtmlnzqohr.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtdmtjbrrs.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtxqgcyrvp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtzxuqhyod.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtprbcnlrs.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtynizpwlf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtxhvmcaoq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtwrpwclxo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtkkpmnddi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtpgggxacf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtklzjbeev.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtxodnxawq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvfpnxize.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtsxxvxxbk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfeddjupv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtxkfflqps.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtabwxqbkc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtcizxrpjw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtpogpdhms.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtwjkllvxz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gteoxsbuzh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtbvytrmto.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtpoxbsxrk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gteahcjoib.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtpsonduwm.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtbaecdilb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtuwnrjbda.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtzikswxte.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtpmhomkqb.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtmcuzoubp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnyusgzk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtfevghmjd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtgkggqivu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gtrmyyvctr.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtuuppadko.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtddpeydbi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtxjvvidvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtytamovgm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gteopcfzja.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtcvnarsnv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtacnquyso.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtxonohcfl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtyksahbus.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtytnuilcx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtqywdcoqe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtctqsqked.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtebsiirwd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtqphxcgun.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtmxlmwdmj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtahxpqzqk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtfvzkibyp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtkpvdbvvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gttgcnyvjk.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtzzxaubvn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtgoxesmgl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljuxkde.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtpmztvurw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtvsvuivjl.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtykkzuelt.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdaorhgre.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtnkyfkgnm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgwbmqwlo.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtheepkudd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxsaifxha.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtebpuisfl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtewmhxbfm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtpcmqflsu.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtijohzbvc.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtgdmwsvfo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtdedfwawn.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsaeotfp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdkusnes.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtpulabqtv.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtbwmnuyaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtatlndbuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtyzovinlf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gterlyxoaz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtajixoybs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtyafveett.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtcpupfvut.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtlmgbzgxy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtzgxthofh.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtebbscovj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gthnrttezr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtbtoooxxa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcneoykv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtdytilrsf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtqcjottaj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtcsvgvzep.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtsmpfhiyz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtwadhzerb.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtcwjzxpdu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtmwrktvxu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtoictogrx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtmeugulgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtgvfjnqra.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gthnzqvvam.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gtjrrnwzqe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtlzqxdqqu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtdwudjuui.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtxyoyjlwx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtvzxypwer.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtvysqhfgf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtoczukqkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtjybgtufj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtobmyzwvi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtkosakbsz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtsfhamcsb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtrqbunbda.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gticbucpcd.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtqkjttipc.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtixkjwbfy.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gttrlhklwb.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtyqbpylhq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtohjntqjx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtvfphhqci.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gtfknoeqro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovbpnxtz.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtgspcomtd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gthgsrrrkz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtdpnjvqsi.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtzbzzoetz.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtakhmsytk.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshnsbegc.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtdiwormmq.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtrklcxezc.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gthwzaadcy.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gttbsydmok.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtbfsmklnd.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtziihonub.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtmgkktals.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtixpklpny.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtjktmbkft.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtfzqfutxg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtpdtapgmi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtraygyfvq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgbpwzaek.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtruyynglm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmiirazkr.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtdjvbipws.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtxwevcdxt.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtrieglmat.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtouqdncrc.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtnprtjbdk.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtxmcfedad.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtjulnzknn.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtjafxhtwc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gthkmwvpav.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtpsbhjjph.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtefiiyssp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtqivxkqoy.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtfmsubiuy.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtpplqvwci.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtbcewbbeq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfiixsltj.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gteydxgwoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfinzbzok.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtjqzkoqqo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtaekkkgze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtginglbbr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtbhlvjrfq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtxihiwzji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtytuzwxgc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtsslmdmkt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtzuiyuuuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtlknenaps.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnngrqtpq.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtgjrqjonq.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtjrbnqkhe.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtyeglgwnd.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtytnfsbfl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtitpnjrxd.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gtochmpmly.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtekztcppq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtsjvdonic.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtpjsyfyzd.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtyrwranso.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtipbuemcg.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtwxyqyeds.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtprftnusu.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtrmdxkirx.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtvahevyag.html


<!-- 参考信息 -->