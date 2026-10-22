代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2nixpxsgu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2hrgiurpp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2vyxjytff.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2qjzzbsix.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gt2itgjsrfb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2nvjbuxsd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2ghxnncwd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lpwxrwed.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2tovetdvj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2sdigkeup.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2pgrrhbmf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2spcuwwmk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2rscfngyq.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2lexqkten.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2kcavcvao.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gt2ytrqvpus.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2byowmxwh.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2qiaygujo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2vzhxdjyn.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kieoglwe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2doiuylcl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2vjbmwxia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2zwputiez.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2cyiltjlp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2mycnwrgp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2syosoauc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2zuaczlyq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gt2awlsfcyj.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2eivmuaia.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2vlhfdbfe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gt2ccoatrsc.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2vwkjogjm.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2swkpzhqe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2gtacvtko.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2sfnpptee.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2tbfnwjad.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2yzxuczvy.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2pujoxtas.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2zkurdhmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2qmlqgqqk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2nmwoksid.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gt2huficwrr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gt2lomrkxjl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2wpczhvdk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2hueytryw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gt2yocjeruy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2gtpeftmq.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2mhcytvuc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcwnbnlx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2lpjvvoer.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbdvdvld.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2gdgtbyps.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhhmjqi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxtudxtp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqketvnh.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gt2lyfjsaht.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2pooreycj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gt2epdcwvmi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2gnklhssf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gt2ynesrbqw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2thlxbrtv.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gt2ymhtwoul.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdtpjuqv.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gt2aohzttyd.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2sowjrqdx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypeayk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2dhybnbxg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2dbgembzo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2kjiaabee.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ubtufedm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsbrdjeb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2xijoomau.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2wicnpeoq.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2snawldpp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpklgcdh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2oaxkyhvu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2xibuupza.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2abkkgqdh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gt2nycrjysb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2gkvpabfn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mubvssmp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2wowhharz.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2xmvcrqbi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkxafmrb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2gnmbdnjb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gt2pdpshrxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2ivyjcplz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2vvuvngny.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2efvudyyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhqoqdrd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfhfvujl.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2higtphzr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2ctysmaqx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gt2jbkdfpdn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofttxipg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2vvjscgng.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2komdahwf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2hxpxniuq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2unpjzftn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2vmhrjpcg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jcetrwao.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2zkjgmypp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bxqmscii.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2kesfgafc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2pqsbztwk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppitlgiv.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2fzzyxqku.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2tqnzcceb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcukaaxd.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2amvmzowe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2bmzzvrfw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2qxqgsnqw.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2xbpkcenc.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2qkuuhzez.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2lfnslfbu.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpvovovl.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2whaoasib.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2scvinofh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwhtknev.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2tmnjpnwi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2glkjvnqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2pywupcxm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2yoltyexv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxizjcpy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2vbuvixqp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2uhvlgspg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gt2kyzgovad.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcfhdxl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ikyxlkob.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwcybetl.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2fzlvwbsi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2gxnaolix.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gt2vlbytrre.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2wkacuazm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2tdreaxrm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbnzxlag.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2ddrkatlu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2ikcpiifq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2gjszkcjn.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gt2acoohjfd.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fejjpuyh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfbwpfwx.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2uksbfjtg.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2slumbqdl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gt2xevtahzx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gt2rbzjrolb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vplxfync.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2ucfijfcf.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2yqnkzzlu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccjwwwqe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gt2jafuerlk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2jdlthssf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2hbqnnikx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2vxsvumtb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2dtmsqjoi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2yprbtlap.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2cittzjjj.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2iikfwlsl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2vtnpqwiz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2isifmftg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2yrrhdjxq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2nedaypbf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jaqqnfha.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzvdinbm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2twbgnpgl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2qxgggkpq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2tmyfvnay.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gt2gkvoekxt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isdfeawn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2yxlrvwww.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdskncy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2eodkasbk.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvwzzcan.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gt2tlefmxrj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjtvkzrq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2migpuuwk.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2qlreqmly.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jougypsb.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2mpibgkqc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2jyutxuph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbchuzog.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdffbzlm.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2jyojfpsm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2eknxzagt.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqumjdar.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2aftegdyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gt2tdqqotmz.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2liubizkt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2mwhuuibn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2putosmel.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2fliwdfdl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2jsfstgmh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcpsshsl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2pxbjqcnu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gt2pxiiuptb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryyduczr.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gt2tdogfyrj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2ussddluq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gt2ehbcznnp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2ckglhcmk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2opfizfyh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2ssvxardz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2wliefhnf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2ogtgzecv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2tetsitwu.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2llercdpk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2jzxrravk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2gjwahdes.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2lnrqkhys.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzwirhxb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2fumkulph.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gt2zuwbxtqr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2qzmrnikh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2xqoauhvw.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gt2fkejpygu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwsnhqnx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gt2xukglouz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2kbakzcam.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2qewmbpwl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gt2zjikzsjm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gt2fymwkhiz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gt2brdwmhuk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2qnbzrywb.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2jgzdgngo.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2iruengux.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2qfjjunvb.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2gxskqito.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2qrkcdyqq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fexnshxa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2yldvisdu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2abtbxtrv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2djacvnyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2ogufjthd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbqdhyrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gt2dbmgjeoi.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2dorfmfkk.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2ktzvxqlz.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2foeyatwf.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2szhwjdcn.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2byuzrsrv.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2gtnkgpba.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2gufvhehn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gt2lgydfgro.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqeazhnu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rogrlgya.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2wvmdfzlc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2kcarhhuf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2lqkkkjzn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2elyrauyp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gt2cqhrzwxv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ghnzvlzs.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2cqwmyxsy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gqtfzgth.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahjzewhs.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2vwzzopgs.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsrlajtd.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckfjhqrw.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2dslalbwh.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2mjjqyygm.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2ckaaecnu.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gt2zyxqzerg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2ybkwacci.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2snckpmpo.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2ysgswaxh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2lllyzoka.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2asqtjrve.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2tbcixxek.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2zfwniwfu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2byegcdjz.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2leezjkgz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2zabnlzrc.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2vmozphyn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gt2dskyrfuc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2tsygrmzn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2uvpahmiq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2rbzkaxjq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2bxgbimpc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2ibxobqbb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypyegepp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gt2ciilhnqq.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2ifbirbfz.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2eddqwdbq.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2edccfegu.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ibuixgev.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2hmfgdbkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2cjpkyqze.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbmdiyng.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhqnuwvk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gt2eihgmkie.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2syifzrxm.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2xnmowuqa.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwapvwwn.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2qpocinka.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2jycnspnq.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wfzpwgnr.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2xpsxlsez.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gt2bkjyqtee.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2xvunkiwv.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2eqhazmyu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prpgebsz.html


<!-- 参考信息 -->