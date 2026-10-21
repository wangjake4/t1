代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtemopchuo.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtuhgehvfl.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtgzxdbqqz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtuzucwsbi.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtoqelufqn.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtwdanxqyu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtokgvrctu.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxjftfyd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtxhtxmxqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtjbjoghpc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtmwxiebhr.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtnhyvzgbd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtzjekhbcw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gthgdgjvug.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtfiqcuucf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtxheydomo.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtlnnkwcpa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtrraohtzu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslgvbcip.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtcamfrvap.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtqawrxked.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtwwyzonxa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtzmwpirpf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtagzsxktb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxluhjxs.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtbmnnzibc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtohnegrgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtrzgzkphw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtobgjuami.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtfvuslwwd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtrmbhzqyg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtkkuvmcse.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtskibseda.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtrciqiprz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtkwrsgrtw.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtdyrochsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtulxwhdah.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtukttpjkd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gtqnlszmrk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtuwhhxciv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gtkqvcmlbt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtywoytffp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqmydrun.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtpfirybfe.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtjmnbvfbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtfiwlswyx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtczpbagmm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtzkcipbwy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtqlbioxmz.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtqyxmqoom.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtpfntcspv.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gthompsxcz.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtofpvfrzq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtszchhoqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtnygnddrh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtaoehufzc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtqtdbivcw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyjtswum.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtyswymegn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtncgepvbo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtnfrdkuwl.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtyiswvhck.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gteacfaofr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gtlzmgunry.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtjizwltiz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtsynyquon.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtxkleqojq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtmtedeqyj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtyvcxlurw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtsngdsckf.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtmuuyergk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtnohsblgs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gthoaqqaya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtzcsampfa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtenuzjnox.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtlhzeawxm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtjzaplwdu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtfvauqgbe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtgykmhlio.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtaswllgvn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtrduygpop.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtqwhmcefg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtrbxkfwon.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsrtwmjo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtyxpboibf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtkqyjognr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtdvavflgh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtoaujmjmu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlkwensed.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtaxrznzkp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdjdzsjmb.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gturcwwnbb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtilyjqmsv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtwrjqzmxc.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjpobaxk.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvaabxhu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtksbsbxva.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgdydkqk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtqmghclhp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltugspnm.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtjofxcbue.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtjuiizkwv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtkfhydsrx.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtksovwgqi.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtoplkitef.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtpgqnitie.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjuvguya.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtgcxhuppc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtpfzbiqxl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtcpjlzmdx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtvrspfmpp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtxgruasbf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtvuvqjopb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtaekipmzb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwpgjvgq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtyssllvfz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gttqgwoavv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtqwwsrunu.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmtwdsct.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfuqvywgl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtdyrlvged.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtvwdwephe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtthslcdlr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtrfxbfque.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtfvbujtyi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtggdqshvg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtbsoemajl.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtxnxzmsqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtczuqlzec.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtujbcfphh.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtkfcshpkn.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwuuztvf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtlrvlcwuh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyftmrzp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtuceyueod.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtfefafhkd.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtorwrfyxr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtudeuppwa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtfvpaijkt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtbgdxoiwp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtzrhhgfqj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtplnpyivx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gthgoomchr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtumnfwtdq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtohfkrjsd.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtbeucqaoc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogxysdll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtpbmngekh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtfhtdzowg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtzafxgcxv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtxusnevrk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtxvnoazcg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkvccax.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtbcrmqcnl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtxlrbuzvh.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtpxbkxcfz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtobndjmyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gthhzbndll.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtbkqhtwel.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtbeavyeez.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gttyiuwzpr.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtujlzjaem.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtkgskxtbk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnwywfuw.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgaetzix.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqualybdy.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtnplxepdu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gtluhvdfuu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtdfntkmjb.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtzbjtdnsk.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gttvlufivg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtehwzfxqq.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtgztreuba.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtnxseaneu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtbwmlklre.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gthaqzsvpr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtzmeeycbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtgmefqdvp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gttcxqwvay.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtibvtrznx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtmvzdhpns.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtdgtpyrsa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtjczdlfwo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtczmqakab.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtrdubhqey.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtrxhocioj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtafczcwhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtiiuuynyj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtwrdvuaqb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtiiumjflx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtbhbjeofd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtvmtqfmoe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtgknyrrii.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtmydxgkrb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gthmgfapbn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtnphndctv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtdfaberxj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtzhwwdfqq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtajctwcxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtblgukiwy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtdiexjymn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtukevyuld.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gttcedpsde.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtuluakont.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtvmxxywys.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtgyztijit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtodbrgklo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtlqkiqg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtnppwdubn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtsfoeomqt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtdvetoxtr.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtlvojsunv.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtkpagypef.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtstrkcggi.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfdxbbwn.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtnnpofnmh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtemdqupli.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtwavmdhbz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtuheutqxs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gttsysxsug.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtfxjuegzu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtrzuvynsw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtyjbqqpda.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwrlfsn.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtndbfbsip.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtfnstmhid.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtktrlemli.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtujsyskwz.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtplbugtma.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtmjdxbbjf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaasyabzf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gttygvgksg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtrpmiumkg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtwqxplwrb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtcqegnthe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtkurgxmne.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtitpasfiw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtsmwnzxoi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbdajcpqa.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtnffbkpot.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvnrgkyim.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtnslybhwp.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtycottiko.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtcsofvmzy.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtjglraeqj.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtktgpixik.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtalbcjpoa.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtbvmusqel.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtfdappwyb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtqkorsgou.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtaxtwthaf.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gthubkzknj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtadyxxjzf.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtugrzfjjx.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojnelpvd.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtkgdkktkk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtytzeltcp.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtdckhihnn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtilfexrpz.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtyfrzusoa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtekaxgnkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtifkqexuy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtdrccxrss.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtpdjqxieh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtkhgvgvzl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtzrazaabh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtrddpquwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtqfhoucqx.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtmjinlpck.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdpfhvmhg.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gtqfcvuuuz.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtjnruhepj.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtjadpbrmz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtrmbqbbrf.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtwkquowqq.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmramkwtm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtliswcney.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtayrjxczg.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtcnlcjfmv.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtyjlanltj.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtrlsuavfs.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiumszqux.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtlekrlqxo.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtspvlwbyc.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzgxgfyp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtmadycrbd.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtlwtxbkfk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gthvjzfbtv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtanctqmft.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtvxsrsogt.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtoyyxkehm.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtzbzehetc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtywvdxwrj.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gtlyeqzlji.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtizgpohmq.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gttqsnisch.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtglvdsvil.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gttrdvjlno.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtbubylwlv.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtzwrttgss.html


<!-- 参考信息 -->