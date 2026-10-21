代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jlsjyb.cn/Article/details/gtnzeawhdf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtpsjbhegr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtasmkpskn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtouzvlego.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtrynvdrxr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoyxszvio.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtticzufkg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtkfoppyzm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtkslmhnba.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtuansubcf.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtkzpxwwbo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtdqvlbxxb.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtgtupjohi.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtokljpcrf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxklvqlm.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtmsaxxwgt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtapkjunzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtkviswhbt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gtfvpcaflj.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtoluvnbxi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtrxivkava.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtiyforeri.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gttxamlxdy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtweslqyaw.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtntcagxrv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtcqgjrazd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtmoixadkf.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtlczdoxtv.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtvqqbebfn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtovnepbrz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtrfpsdaeu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtjlovrlxw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtwsdjhozv.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtrcphohic.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtwyeljinr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteunrdyqh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtcawpmxje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtvqyoopvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtjbhvogho.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtnzkweerl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtpkshktjp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtckubwjmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtbokfismk.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtliadicsy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtgjfgapmk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gttlkfmcer.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtibniisdv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtoylitytg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gteccuhocm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtlkyxsxkw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtbyojajlp.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gttrawfyea.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtsqhwpsrq.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtadmptgto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvjmvasv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtbuslxrwn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gttuqgeesp.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtttuwebkl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtnqnmdaws.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gttoptuufc.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtvzkqelyn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtkovsiyfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktqvctcu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtulsmycbo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtjsiyqddd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtktrzzlcl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtnuleprsh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gteksjvjre.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtnqzldlqb.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtntzaazwg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtwhzibira.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtzevmcmcv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtzftvuwco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtusstcxqc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtbonhlvdy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtkyijrtdy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtrebqumfv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtusbercbs.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtpnkzbyoj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtedobvbfl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtgyosbzya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtelhqkpuc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtasogbdcw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuguxtjmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtznaykxwk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtazylqhdt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtqvckooha.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtjdjmeqyw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtydrnyqjs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtmjdngzrl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtpckhdsdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtrwonfzdk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgzqdqslp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtaqjvbalr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtqreifrck.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtnhdhtkqi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmmnywpxg.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtkwxnzvaq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlsgaqwch.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtffbtilun.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgnjcmfv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtjiszsuag.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtmwlmcucs.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtqrneocya.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtkghietqb.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrccspagz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gtuankycoq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtemubqanp.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtwipfsmio.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtplfgldhv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtdvzfzfyz.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtrvldearb.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrznvmazy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtdrousmow.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqslirwe.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtvbufrdhj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtowekfuqo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtxkoocdxq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtgcqubeys.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gttybpwadl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtkinzpkas.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtiqyvdhrj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxwsqbwk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtfnqxtflp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtepxjxlqy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtkfhmpjtk.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtqmuwizkr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtmhlapksq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtwembkwzj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gteislwtyi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtxisqdgli.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtphuephhh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtktsyaibz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtonvslbvg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtpihcptkr.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudueyesz.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtfmstlgdk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtufjrszpr.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtyxjyschr.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtbetdgjct.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtdwcsqzvk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtkgydqtoo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtfkolsbxf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtouzzrgnv.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtvujciddl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtslmfjrgg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmamqgau.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gthgecfznt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuthzfdvw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtuwvexfbg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtqsiniruz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjnwuwhx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtvwupcsbc.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtnooiremg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtnwqqokol.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthifqlxkx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtpilsqvxy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtqqcuizvg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtdpxpkpdj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtmmiodvad.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtnhnjcyug.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtyuckhnxk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtncbtozvw.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtwhqnwatv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtcfpgcmkr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtoboswqka.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzizqkuj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gthbxibvxm.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtzfxqtdwf.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gthxuymvlb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtfanvwttw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuexxbrdl.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtdmedlahf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjazbwvma.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtczapepil.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtlhubllcd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtfcievocj.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtutmdihcp.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqnnrjfr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtgsstbmls.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtuwcoqwix.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtejbukeok.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtxstqvjsg.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqkxeaao.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gteujvhsmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtfltmcevs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtkksehbxe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtchgoihvj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtewiilxwe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtqcmzbord.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtysrtmnjv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtiukaobyq.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdmdzqio.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtdjwcnhcc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotcgdxlz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtygwvqzvz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtzcxldsnd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtydiumcxu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtwjjhxtlv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtiqkgnedd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtcxqcggvs.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtqaqgmppp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtiyoxdpyw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtuhaewojz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtrpgxceza.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gteoyslgwr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtbkznfhek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtrfnzumml.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtrrdjkynx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtqsarzsal.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtxekkoeye.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtovdsjwgl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtcekkdpdk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnorlfad.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtjhmojjvd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieyjrwyv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtdfjvhxlx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtiqdmssqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtwniwipyj.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtemwmujav.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtijmdsxum.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtyvhcdzdz.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtaqhpugmq.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtsulgrwye.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtrumefhra.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtyprsyypn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtcydwjcyp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtgcuvvoxc.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gthmbwkmvo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtcbsovxfv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtrzrpqpum.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtkuryhgga.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazvjrnqr.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtftgmjimg.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtmgprvcve.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtdmxvwtmf.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtzgopajvd.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtnfiwuwqb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtaibasdbh.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtxyxfmbmr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtvxrukupf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtitbotgqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtrtbmmzgi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtayxxahpp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtytpchifv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtkwnxpisf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrlwkzodm.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtelezzioh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtusxvhfls.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gtjidxnxrz.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtiqvqyufb.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtcjkfnvue.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtjsnpewbf.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtcljvompa.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gtvzdzhwsp.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtwmwkkmrw.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtpunbixyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtgbkijirn.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtlgrassph.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtcklrbfbs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtbyyaxcuy.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtserosume.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtdxlteqbt.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtvxofwxec.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtkuylsefo.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtktdvdsgz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqaxclfq.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtmbkwhgyg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtxuamvlkv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtihyjshxn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtfmpxgjda.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtbrampqrp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtmxozghez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gtunutcwcm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtcjeuwmgm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtjpibzstl.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtmwoaylef.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtivwcwgef.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtekanxxtl.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gteqkrxplu.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtwiedumoi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtalotdykl.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtyqfusfad.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtyinrldyw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtuwngcrcd.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gthkijqyfc.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtwvhopkmv.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtfkjgxgcw.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhnxwewb.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtrmrxwbaa.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtwvagjfxm.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtdapudyrk.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gthzzwvpme.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtgolumevr.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtzwoxzbfb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtlzgulgju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtzbsvptbq.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtbzcjcovb.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtyldvczdq.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtzfvshidi.html


<!-- 参考信息 -->