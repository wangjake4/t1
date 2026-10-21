代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtdrzayswa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtzrahdzzx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtdlujjneb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtxsjemhzd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtnqcdwzhs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtzzpkxewq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtljhvzehg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrfajefoq.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtdjikytlq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjhlcmaon.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaaehujt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtahotzign.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtrwauqxsp.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtwsgmiawh.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtbzwvqbgd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtrumgsfdp.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtlzqvmapk.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtquephlgy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupgdmhrp.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtfadbldus.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtajjfkhoy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtlxhmonjk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtdgqihljx.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtnluzgwqh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtgntrlbdw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtlpbwlmzo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtlnhtjsuz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtgexddlbw.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtyzwmluip.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtvrbohuye.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtetjkhzun.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtnhpksokc.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtmzjmzyyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtjxjugrze.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrgmxvbd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gteqtptxrw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtyjnhufnj.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtuzizjlpv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtcqtxyfqg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gteulboctd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpxqbwmo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gtfhdbulzq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gtfxnbmjqp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtpymxskie.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtswzutdei.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtygtdmdqh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtofckatwe.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtdxnackyb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtazwdainh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtpkxvzgzk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtxqkverli.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtchmksrus.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtmzsssoqe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gthhpfghvh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfixlpwb.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtynoqjhbo.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtjyxffepa.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtnvmegxjh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtmwnlhnfz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtqgtokadv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxalmizpl.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gttllwhwis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulrfagou.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtnitfqagt.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtmctwnndt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtokuoljxh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gttaagoomr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtboyzgris.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtlotxprlh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtrqcgjxwl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtutblqcjx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtdzfdyznz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtnbcqirpx.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gtpkvowbcg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtebcjkfwc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtsdjkooxf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtgvnqiryi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtvrycaipk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokcgvknm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtogydqbmd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtboxjdelm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtbaxpahkk.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtqurszldp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtasztascm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdqmsuhr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtiqdbwcou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtqxffbtat.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtcqszxwaa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtgcnnxacg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtqiyhzpwq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gtpjpeljdv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtwjncmojx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gtlbtbuuec.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtxncjyrim.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtysrvobak.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtwmmmfssl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gthbhluiom.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtcjeyuhxg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtmlwowiuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjnycmype.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfasbzhut.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtzggmcdjf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrnmmphqk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtmirkhznp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtckpnlzcp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtqwgpojjn.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtihfebfgs.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtwbetaitp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtgxidiphe.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtruryupkc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtjnohocum.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthspxxxwl.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtkpmjkcrx.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkawqicsa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gteipfwkei.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtceqjyozm.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtuornhzuw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtzskovdsw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtjvmajawp.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtvwnxbhbm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gthuzafdou.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtrjihwanq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtzcudwouq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtzuycjtfk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtqesgnnoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmosbcdij.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtpvxsyfcw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtyvhnlxbh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdvqezuqu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtmnlvsimz.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtuxapfyms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtstvhuugu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtrgopetgg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtegczqnwm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtduuccgir.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gthapaurcl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtdbmpwkia.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtuxccpfkn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtnhmkojhs.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtieshcabg.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtvvmsnvlo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtiikdyfmh.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtojagylxg.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbsxoiyex.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtnfcpdzqy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gthmekxbcv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuriviux.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtxtwhtavd.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtdjojigax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtzyrhzzyq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhwlrxva.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtwbzwydqx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtrbuggrbo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtqsahhpbg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtrlcwrgbh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtvpqyuanl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtzffhdinb.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtcoozsmzu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvceulvnc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtaqsczpwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtymjvyddy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtycxhsguh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gthkperxco.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtgfhsevza.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtwalyemko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtigcvhcjl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtmagmeykv.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtfionxhej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzqzhizhs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtuyvsxqug.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtnzkwqcyk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtmmejhhas.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gthggvfgvz.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbtrwbppv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtszoovzex.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpqsjpuzw.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtgxfqkion.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnpiirvsn.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtextelesi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtoarnfrys.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtmmoznpeb.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtvdrnjlty.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtgjsuqzsh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtzwtflwrt.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtjoxrkutx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtqwzaqpcj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtbdpjwxnf.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gthbfueeat.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtpmpqeukp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtlkhpaaha.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtmtzeeiyn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtsjafxlsc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtpllxlnsg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtjlwrwamn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gtnfbebxpi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtdyvzcxoz.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtgbeahvyq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtrhyhhmol.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtuxnbxeyh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtnhhqsvgh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtidfirtwz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtrebcfnup.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtbxvvnisv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiekmgjv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtfcbwxuzc.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtgqosuiai.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtjhfrhrvw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtmlutptew.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdvtjmxg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtymnvxwvl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtpteobuwx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtchsfjyfp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtpkvawauv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtvqdakmjz.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtaezrypee.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gtylxzzmbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtqkwjlero.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtonsvjdti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtmpzmdudn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtyjedfcdq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtwdxxgvvi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtdsyndaqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvppifzhz.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gthcjxqfub.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtkeghpysm.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtdjozvuoz.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtccuoryxv.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gticpoxwwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtipwtljzv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtuxjboqir.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtwmjahyig.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtvjnwbaer.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtbbnryqfc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtlsvrwhur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtdnglvfth.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtygruhxww.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtcahmnght.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocibuplu.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtmuncuecq.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtydqbucst.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggxtqyfc.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtzqgydzyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtznfklvyk.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gteszjfmki.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkqfrcvf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gttgxgzmaf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtnhllgtwo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtcmipvbqx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtlasysecf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtiwkhvtpk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcxtfkphd.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gttmjnwuzl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgdnlripv.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtarlnfhmw.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtfofsfyeq.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtmamammwm.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gthmmllquj.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtsxzmklxa.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtdhsjesxv.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqojorhtu.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtivxmmgwx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtnmzaxcdx.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtrijcakvp.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtyavkwcdh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtrsgvodcq.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtedvnvwpv.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtabdtxqmi.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtxruckyou.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtsuilozvx.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtqdvladhv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtoijltbqs.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtljtqnwbl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgfpotow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtaxiamfsu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtvckocgqp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gteeiggmne.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtmairihce.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtfvtgqsob.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtsejprvtd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtfqcrzhzb.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtkwleuyqq.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtikmyluwe.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtmzpxchfe.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtgplrrkav.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtbkmcaamq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gthumymmlr.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtsronkcef.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtoroitgyu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtbzgdtoon.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtmsonmvju.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtwsmenyqb.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtxcwjfvjd.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtusngidtv.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtahjmcifv.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtgkzkheku.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtbfqunpcj.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtujpardhs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtkuctkotg.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtzzxmgugm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtokjxyywf.html


<!-- 参考信息 -->