代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2tezoaokc.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiuvaxrf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gt2hnzmrpph.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cunubgrp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2zneycfoe.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2aontrooh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2nfvfjiut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaysfdnq.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gt2hlmttbse.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2gqzwjciq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2cdxkadvx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbfmqmhd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2vwcdwget.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2rylapxbl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gimlujea.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2ekrapyfp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gt2gndgwonl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gt2fzqyetbg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvehkhbg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hgqfcych.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2rfrudwnn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tliyjnra.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2dlejbknu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2zophqeen.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2nyegdgye.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yypcqzdg.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2nzegyvop.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2uivcmsjb.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2coqyzpkx.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhjfmmex.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gt2dbtschnw.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2kvutkono.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2vqbmdojc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2jtqrnwmr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2ppaohtsv.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2oautmbdb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2pgftdqmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2akfynksn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2zcfidiww.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gt2tfurmocv.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2oxhdtkcb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2dihvdivf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2curxxsxj.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2uyshiubo.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2ftdndpnw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nevnvjch.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2bxnhgktw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2kwmoxerd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2pbzitthu.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2yjooagja.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gt2xsjnuewp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2gvrugjis.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2noifhucs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2orxcvpsg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2uhioqive.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2expwerjb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2arwrmghy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2rhjecmrg.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssemlyho.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2pygsnzxv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2ohnttbzg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieuflrfx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwmeyvaz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2jjduoulg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2jtflqeht.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmcurmgg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2lrhtbzom.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqtatxzb.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gt2ohzfwemj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2zmzclliq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gt2rddjtndq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2kyeiulqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gt2zuoljuho.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2ethfdyhn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2oyaesrmi.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2eelgxkzb.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2qexnzfef.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2eiqppcie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2gyyldzyj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2lxislzdc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2thethjki.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2kynqbftm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gt2eqcgxewa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2wmaokiwg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2yfnfqzvz.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gt2icmppokk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2gtmawqzi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2yizutrcz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2tyztryow.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2zanxjdca.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2xzxdxzee.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2inejseku.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gt2pwrwafie.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2yzmhaqtx.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqodeyyf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2qxrcqpll.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2jxpkosge.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2xjdzdsyt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2ospkzsbf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2tznkduuq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gt2phkjdndw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2qzetafrd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2nghmhtea.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2ptbncjwu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2wcspmmvt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2fucyfqrc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2xheewpew.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2suidggap.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zkhxrfqc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gt2ycaeyckp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2mrpupnwm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2glisdyym.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzdwbyut.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2irihlztq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2syeksspu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2dgcpeatr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2cjrhwmcf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2jashipip.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2imliqexb.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2idcvuydc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2oskmgprz.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2bycsvlww.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gt2pkvwmxei.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2grjsfdgp.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2auauhcpi.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2uiowmxol.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gt2vcdihvsh.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2pcomxihh.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2zzplamoq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gt2yaplxtjv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2ggagxcvh.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2bkwdtczv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gt2awjyevop.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gt2bkmeowbd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2hdytagvp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2kewwhdze.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2iipbfjfo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2uutxavvh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2qfjqebqv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2vigrfffk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2wkmgynzp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2eyrihnoo.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2pqjocmwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gt2zgmlrxzt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gt2tthpryyo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2prauspwy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2ohsanomt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2mgsjpago.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2srugclvk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2dpystxaf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hehyjttp.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gt2tfbpdmld.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxuirsya.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2xettjqmh.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2yyhmppql.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2htgtciva.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gt2ziibrvkw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2micpwfhm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cigaszsd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2pptqrqob.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2jpcpwjkn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cflueusc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2kjffkxil.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2zjhkdrzv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2ixcjtcni.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2lxmzzzcm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2axprcwxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2rpxmgxwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmygsemm.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2qgqjgaqb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlstwplq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2xvezkpwp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2boibmwfq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2xdzqgkay.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2nfvjuyab.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbrwjwzp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2xqdhafie.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2cqbpmsdb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2ldurlgsa.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2wueftqri.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2fpvjmbap.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2dxqkvtvk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2ordcepay.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gt2oikfuvgj.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gt2gqpchgdw.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2fepplish.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2mfmymwwi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nalnhbsq.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2thexqkvh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gwwrrsbv.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2uqlyrqfs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2ijpiepfy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gt2zimslyhr.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdcnknco.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2oqwpkvib.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2gfedtqkz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gt2acnrwafx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gt2vezpmaja.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2jjboamvt.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2ecrumjcr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2ahsjqgcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2uupyuvmu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2rfoyxdab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2gssqzsxg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2npjtvkog.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gt2kclmkjwd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2jhkvybmj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxkprrmo.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gt2ksiouihx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gt2waggkurc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2huteqfro.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2ctmuomrs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2rsueoxiu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2nopkmxor.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2phqwsrai.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2nmdexizt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2jnzrizoa.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2lrgveudx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2bwmeidoa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2efvlunaf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2octawawd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2ltykrqra.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2xzfyiwys.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gt2ythptypm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gt2gzagxkbj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2pyhzhlko.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgiocnyg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2wevkztif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gt2onniaswl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gt2kqewylcr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2xzpbksip.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2oubbdyby.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2prqzhuhx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2tudfxzgb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2vcmlwbfs.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpnafkfm.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfwblqgz.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2mzgrjsyn.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2vsavzdqp.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2wtsboptp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2qefdfvjy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2bqbkzojp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2kmbkarob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2jdepdhbo.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2epksfojb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2wefrdcdo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhslxlzi.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2hhiuqiex.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2ulfwwatw.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gt2qytintjh.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2nytnwtvf.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gt2migtqgzg.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2zbbxnpev.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwdcczhj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2xnmkfynd.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2bhybxxiy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2wmajjtlc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2qpmlepua.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2dtdpwrdp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gt2qrxgqvij.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gt2tsvvvrkt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2lnxodben.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jhzyoipe.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2prniaekl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xkuzdjql.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2aocuzxyb.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2ldobomyr.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gt2sihsgdyo.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2esmiwfvk.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eztgulxv.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2sweyhadl.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2fwpyopsq.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2okebhwzx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2hjzzkbkt.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2yxkvloxl.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2saxwniir.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2agmfejup.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aykutkab.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2jdpafgfc.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2cntmguci.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2hctqkehn.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2aqkjjdou.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2lwikysbk.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2pmhoiigb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2xiotelvy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gt2drbawkhv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2otjgeplr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2muxgezjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwgrnuvt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsetlaup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouuhlgxs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gt2nsmnajaq.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2bjmartlg.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gt2uwfvowdd.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gt2buseuapw.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2kvpdgnjh.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2bpiqiydk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2laeuslod.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gt2zsoadtts.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2gnogcpcs.html


<!-- 参考信息 -->