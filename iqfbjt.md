代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2zcdfbetb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2eyyrblws.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2kjmxtzbe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2vrhcuasr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2tvfkjvkj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2eovngjlg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2sfilpvqe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2yfbmlffn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gt2yvpggdjn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gt2vagrpkfz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2pmldujgf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xaiuxptv.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2tcufsnha.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ddxohodn.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gt2uekhudla.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2pssblpoq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2nctusmaf.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2rnaiqcev.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2gklancrz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2tyhqudfq.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfaoavky.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gt2kxxulxrq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2hkhdotqh.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsppjljm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2khlckxup.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2yyozakex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gt2ibzevwki.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gt2hdpimfaq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2mvcvimgu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2iwctzwiw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2vjxetmxg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gt2ysyiytuu.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2qwwftrna.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gt2yummfcuw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gt2hdrhyhzu.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2kmuwypue.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2uestfoyc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2jlakhrtj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2dfytmtmi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2fmndwfas.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2bkvrujgl.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klbsmrqy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhjrmafc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2mgrhkahq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2khgfnisa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2rlpdhfrg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2fpnwlqmr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zztsesau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2baudxgzn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipvckilt.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubhsgmat.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gt2xpcwzude.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2kwvwdfvu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2epfsmhvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2sadenmtl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2vdpyofqm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gt2mxojqxeu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2dphazaeb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2buctpylv.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2ikuwgggx.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2izyuxubw.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gt2dvxnespq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2jfpccjct.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2dmvovwqw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gt2sxxvcuyt.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2cppkanrv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2zlamkdzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2ymhejxas.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gt2sivbmfor.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2dwrdoccx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2ztkcgrmg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2vszwevau.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpaxdjvp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2xyslznhn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwzrjadf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2qcelttro.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2syigdndf.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2ipurkvgr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2csiyfbad.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2bxwokhow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2ldvzqaik.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2wydfzomn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2pavuvjag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2wpkwlgbm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcbwcjjo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gt2giolbmoj.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2jepjmcfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2ktsiyvwd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2jxdcxipm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2jsemytqw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2lkzdilll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnyhipwy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gt2euqyhwnf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2kmdgcyab.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2hmhdenvo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2vsbzyxrk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyybotyq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2ycvpxusy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2nptvbsvw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2rpyuocva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gt2nyaqcedf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gt2swddmimo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2ycfxmgsf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2umfufpuv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jzwmpjtm.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2obajvgrk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2aycsycnf.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypxkuagv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2idsajvor.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2szrgxiin.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2szciiopz.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2lsozimux.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2trhfjwpc.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2uwudrbko.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gt2hbwjgghx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2qnbtzxyf.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2jidzxzdf.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2dpbxwged.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2nzycpnjn.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2vhqnjuul.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2xctcwwaf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2uksmpmeu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcfrxukq.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2malocjyp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gt2dbtqibxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwxchknd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2jictswmi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2vpnwaqsk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbvqpfqs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2enouavks.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nrzddcei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2ouslkenl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkezxcxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gt2xswtmgxf.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2kmdywxah.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqgzgrbx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2kjqyxdmh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2srklpsmo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2ejseojwt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2xamotzwp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2iaahkwxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjefnoax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gt2ppormyam.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2nnpdcakb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2jxnipnkq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2bbrxocdk.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2oydzwbtn.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2darawzrh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gt2mincdurp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2hzgnffnt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2ilkkhwlp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2rxpnuwjf.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdjndwhx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2likeobew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gt2gmneavfw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2bfkirans.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2hdcgnsbs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2iiffdcnp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2ctopilru.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2lxmygzmx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2peidowvj.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gt2vrzzagoy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2dimkazvf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2rlyrsgqo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2aisqtwhn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2donpkeru.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2padqsumr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2ijqdakya.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.iojbl.cn/Article/details/gt2ygfmbsmb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2yppxvzkp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gt2qpouvoqr.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gt2anyokcjm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2fiooqynk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gt2rpxvzxic.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2utrgwhcg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2hjvisovt.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihedmgsd.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2knyvnlgq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2nfbqztuc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yknobqhk.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2thhpfrkd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2dqllzplh.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gt2kksatblh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2vksqibav.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuocutmh.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2inzyavxl.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2rmqvvysd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gt2xgxjwdej.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2qoborqjd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2gidnswkd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2lthmostc.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2lqrpvkux.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2bqhhpwxn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gt2udnwejgy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2ecohvddo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2omnlusea.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2lweadeos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cordvnab.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gt2irkwwbqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2oscbihuk.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gt2pdclkrbt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gt2qtcagvmc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gt2wmqavkwe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftcybxyp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2msocqkcr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2bryfjhxg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2exfaygxj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gt2umponxzr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2pwcdmaen.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2qdqdmozh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2hckgrbho.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2oqwyyqkd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2kfvvhjmy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2xhbhxzwc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2qohrkuoh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2gqubanta.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gt2xrmxttcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2ymgeqnui.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjajmznj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2fruvhvcz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2idxqzldj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2rlzuqqsy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqprfura.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gt2zoogmhpa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gt2jxzozdrz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2dfwlglvv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2dvkyeqzf.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gt2llrxcyiq.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2fvsixlum.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2nxnyaxtr.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2qtmpgfhv.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2bzxhsxhe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2nnoqaeid.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2stmrximy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gt2yiegsmbp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2kvphjefc.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2upwwdbjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2afogexrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvtmejna.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2effcwcuv.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2rrezmdgj.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2skkmcnqg.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2ufwitmcu.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gt2aurglbod.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjgrjcjv.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gt2vavilkvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2hdbffsqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwducojs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gt2rcckgznm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2rovevrat.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gt2vdjavbzn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gt2efjzfdqm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gt2qyvmtajc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2hmvseout.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tzlxuqgf.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2mahiezpu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tolcutlf.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2qugctnjc.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2kuadndqk.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2dssbraai.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2yygdvyso.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2mbwagszt.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2ykajrhlp.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2tqcumjfj.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gt2vbekjbsd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2yuqybdjq.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2grkjddeh.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdvfjzxn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2hklltfmj.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2aqafjyjx.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2hassbdbw.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2fncyvlaf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2rvjcwcyn.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gt2wjevabow.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2layradlm.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gt2zmmccnib.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2scprwfky.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2bjxqmoax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jheegkvf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2abstjubi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gt2ldyyfrwl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlfnsxqx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2jhwajfuh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2wkfdnwhe.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gt2uljlfglu.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2aqheajen.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2vsrrlgzf.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2qvsaetmv.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehpfhcwk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2ognuycis.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2fwiooozi.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2sjioodxh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjmgiohx.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqzobqig.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2yrabkxqx.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2jusvkyzt.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2uflakqyd.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2kkjdbvmp.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wgqnwopj.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2gcipwttn.html


<!-- 参考信息 -->