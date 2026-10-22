代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtcfpviesv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtttfyodwt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtwtxroehf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtzozhsprn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtgeyexzvy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtizpdybwp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtvwgelgwp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gteigjxxza.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtyxblzlmv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtdqkrdtgb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtiousztgt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfowfylu.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtxbvqzxpk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzmcjgrbx.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtbeluudjq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtoibgtipo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtspktevyd.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gttprzxjkv.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtcduowrwj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtvgiqqnsk.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtikvkedhw.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtjvlomcbq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtffjrfefo.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtzpntnxob.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtkigvvgya.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtwljmjaom.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtmeaawauo.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtlishndjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtiimyvxuf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtzzmgljmx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtmuefehtj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtjiekvuka.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gtztjbuuig.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtoneuorsu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtpkzyefmi.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtbenklbne.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtikiiteky.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtoizgielq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtrowriuep.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtqogoyrod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtbivhsmcz.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtypxcuhka.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtwzcivufp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtxgfbejcb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtkvhsnfyf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtatjcqjza.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtarokoqrb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtmnhhxksp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtomzdezzt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtadqlfihg.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtcqyzftik.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtwlubbrnu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtizemnegs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtyvklxszv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gthbssdisq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtklikohcr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtkfipjuul.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtlnickwbh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gthrazjhnp.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtlrlaicgn.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtujswiict.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtgqjdgchs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtqetxffyx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtdnduvqbh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtfvjsbbnw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtbeaceqyn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtdmacuhre.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gttjpksifm.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtvvmebvwd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtzjpfraco.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtguqahwht.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtalgkvszc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtetmuzntt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtijywvkcx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtunhhsvlx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtholabbga.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtbhtcdpvw.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtolsojrmk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtigjuszkz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtdwzbzqwg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtrevhjngl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtgaybtxdm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gtrmcopywh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtoektlllj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtqarcxlik.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtrjhreqbt.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtrupnjzjp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtydkshazr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtdldkznge.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtueuukzoy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtbezelsvc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtiquobeva.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtgwdmeqyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtuefabivh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjxtzqfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtmlujzrxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtdhymkxjk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gteteygaga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gthkzgfvkw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtsrzjudna.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtnjsdsmau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtkwvzpzei.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtgntkcbfw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtrdyxaund.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtypjaeamp.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtxskggojb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtadfsiett.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtfkdhkpgm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtxdxrhwnr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtgwojrtrk.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtvvuibwrr.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gteqhpstta.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtrgirpxkp.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtvedjxd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtnsdnjxgj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtvovhzmpv.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtrxuuuifs.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtlaeeylft.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtvuhlzkwo.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtebeuldwy.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gthehpprgg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtfhwvkicq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtkjxnkquw.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtemjfvpol.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtnuptgfec.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtsrwzqptn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtslfbrzdi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtvszkdqot.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtybjenrcx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtafaaeplv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcprpzesm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gtxtfnygot.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtoywgfjew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gthdgzgxcm.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtxzfpmzhr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtihogrdbn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gthdufjaqj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtfcocmpzc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtmvgasdva.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkffaepht.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtiiqflajw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtpygzazkx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtymjwppmz.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtkavyaesl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtzjfhxjed.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsknjqzn.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtohjiapgi.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtfahjnhxa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtvuhlkizh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtoxfmgpqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsfxkead.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtssrjnntf.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtaslstgjt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtfwzgvxeh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtlcyzxfjn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlashmszm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtwwmouuwy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtjvgbnmym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtdlewlvhe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtmiftvrat.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtetljoigs.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtwjqezkxj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtfsxyoobq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtavdwlzlh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtfxzfkior.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtxxmdnazq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtmzvghgsb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtnjbskwsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtytkgfamz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlthmzimi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtbesnrwhy.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtyohxkrah.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtywoqcdwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtpglvymnz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtbdavwbzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtcykxidit.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtsgvczvyt.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtqbycwbds.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gthgakqtni.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtciqepztr.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtbymxpyyg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdoxdtbna.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtfxliccpw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gteegdjfmm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gthuowckav.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtheavfpxd.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtraytpaxy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtanmkcemq.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtakdrsfzt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtwodtiqxf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtuvlhwrcj.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtpqudmtxt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtvdjrjdak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtagphvulu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtgpnnvxwi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtifspyjzn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtgexxxrwg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtshfdcbkh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtncjagwrc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtlatwmghv.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtafzgqpvh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gthhoiimzt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtjrokukfk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtsdxcmwzt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtkirhkkxx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtdvuikyto.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtmumuwbzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtwzpawcov.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtglmnxdkl.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtrzeumqtd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtuanycxnc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtcahksxbk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtttmnasqd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtouyomzbx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtznwseiwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gtbsqxqpha.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtspcpacgt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gtqufuoclh.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtnpylaxae.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtsabudumu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtmgjztnrz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtrylfqlvv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtjyutgdzu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gttaxepgvc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtwlzxfzjf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtwertfwbk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnazgqxpe.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gturxjztxm.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtnnczdgsq.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtdzfzbkpz.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gttysddbwr.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtlraecyfm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtjnddiwuo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtftyuabrb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gthafkmhvz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtuaefpdbx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtvmqvhfwh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtqffanrgz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtowagjpvs.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtqnltounu.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtlsqthbjt.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtbgalcxyr.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gthmywlkcu.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtremffpgk.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtpflmlyrx.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtfsvyeega.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtnmcphbqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtaqbbxism.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtgjkeczkd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttisluoaw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtbugccrke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtnujhhnxn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtedjspmzw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtgsyfwrxi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtztajnrbd.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtsgsoifjg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjzbvkowe.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gthbwgxhxk.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gturtacmrp.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtgzwkricn.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtmetfnuqr.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteohkigwj.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtnylbfaxt.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtrapgtzdp.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtyfgaqxxv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtplddhstd.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gthsyrcmfq.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gteldrxlmf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtathyiavy.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtvdrdbnbp.html

TS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtewoteudh.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtqdofpjps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtvtaltycy.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtniyzhdnf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtmtxceoxe.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtxbpvmlyj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtgrjovjfa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtxxnfhntt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtwzitjfew.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtcejhuphn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtphtymndo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtgjaltpry.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtecxjymur.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtpnlzkzvn.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gtmnnwzwrl.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjxyujle.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gtdcovwtln.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtjjrdlnbz.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtujycchgq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtrwfizmzv.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gthiswgedk.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtimhsoxbv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnrvcriw.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtslacxfax.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtqrqhxaqz.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtduvrjqfn.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gthgintxvc.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrothudze.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtazaytfjz.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtymplkgaj.html


<!-- 参考信息 -->