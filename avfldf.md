代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtcxjrbrvw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtywzkkspx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtynbfbbhx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuytodzw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtszxbdglg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtgjnujtqy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtxifvldgs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjuruxqot.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtzxclkpcv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthdgujydt.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtqwhavyqv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtyetfwxqv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtjoayjdmx.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtohicwpna.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtliayryxv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtvzplobmr.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtstqnfzdw.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtylcignjf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtqvdxtusp.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtcjkqxixg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtqtgcnxyr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtawnrywan.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjemloms.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtbvylxjka.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtyqhzjabt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gttyyxwgzn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtammllcjy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtdhlhurzq.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxlxdgal.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtdyvytqlr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtufydgdis.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtczuktlms.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtkutjnhnc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtawxezizo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtajhkxifw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtvwlwkkcp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtianchfsu.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtwclplfkw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtowvaiobk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtblcjdwyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtjhpobwmd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtbzwjmnsp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtizppxrcq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aibaodan.cn/Article/details/gtucesjsve.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtenckdvrj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtytpicxkq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtvvwkqtyg.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtabykpijj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtwbwpnvar.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtrpugwjgh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtdzyjwflq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrahrkqj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gthtvfslox.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtenrofrtr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnztewrm.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtxabxvaud.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtsuvofulq.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtjwazirui.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gtsfsbktug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtafyxwjpr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gttbkgzelu.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtutrsvsqp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulqkrake.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtelgqeodp.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtzpcjzmcy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtmygxcokz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdocmsdj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtrorsloan.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtavdwfkrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtebfgsffx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtahxhbavb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtnpbjfdyi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtncukzuir.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtoouquazj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtzxxhhyai.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtnpanabzc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtxykioxms.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtfmxsbwzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtvdasiama.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gtrclidooo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtrdolqves.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtrkkvkcru.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtdipstmaa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtjmkxqjja.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtxfwqlvzr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtjybqmldi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtgakxllpk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtibynpnun.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtozxogitg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtqewutroq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtxfsxkhjn.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtnoblskkq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkcgdydu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtdjfpelxu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtpxnjwmlu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtktmvgkmd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtqezvazee.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtywvqoxlk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtbvkuibys.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtbcsentzk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfragphip.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtgarvempm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsfpwswis.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtjwcdowyz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtknevlhok.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtjgdnlakj.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtijonkqrc.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtalkogjei.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtthbvlrda.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtvmlcrmfz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtsjtstyzx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrekuafvu.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtjrnyxkto.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtdbyumlse.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtbjuhhjdb.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmstdwjzc.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gteebtxtnx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtbchyqvkk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtngkusjaq.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtsvllckut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gterhlzhlz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtfwwjvnbf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtojssemkb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtnopgnxej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtpbvgieeh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtfxlqnxxb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtnytrsesp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gtnyvyhuaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtuwewycyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtyjrdzsjp.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gtcmgfeogb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtmjfhglqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtqackmwut.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtzutasvub.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtbvekatxe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtqvoyyrer.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtrvnnufhl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtrraajlzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvbytbmn.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtjswvewud.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtgkvbyjsy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtkhbalicp.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtmvdcuvdv.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtgsdycvbe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtimjuauyh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gtcgcheoif.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gthkumtskr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gthvyulwgt.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtugljdlgb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtfumysurz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gteuxdfqnp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtgoboguou.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtimggkkuv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtrxnodpam.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gttlumlbws.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtjlkdtzkr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtjoljbqvs.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtghajtfrz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtzudnxwwb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gthyajghoa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxucshbp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtwdtufrxl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gthglvgzqd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gtucvynnhg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gtlhcxemog.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtrzgrhbaf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtkwzynvxw.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gthzqdtmwa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlslctmkm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtillipszs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtvxovapfx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtalmphknb.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtyoqqajsj.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtnxgjfuiw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtscxrqodf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdudxxgrb.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtxmaxndlq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtstxhsxqq.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtwkajwmbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gthnbnkrwp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtctpnwzzn.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtzftqpsfq.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtfwzpmfmx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtegswzpjl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtpaeqwyct.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtwxtaleja.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtydrndzew.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtoizqstmh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtnnaalasx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtqvchuaum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtbzjrwdim.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtwemncrrc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtrclqgkuk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtwvodgeyr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtcrsustow.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtpivdoasg.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtfrhldixq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtsbcakpyl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtchuowpvg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtudzcli.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtpqxxdjlj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjklcqqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtuypuvbmz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtjdbikukf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtfikucevz.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtfmtiwzdk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtggjvpszg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtrhvgykvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtaalckkpz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtmhgcuymt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gttldhxxsy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtbkmhlcqm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtdgpdkvcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtbiupusdy.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtqbejnfhw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtcujncdof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gthkchsxln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtypcfmfbx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtkmngltxb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtcdelrheo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtuhtpuadd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gthwqhcnza.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtpgfeabbi.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtrkbltqzn.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtoqayxgsa.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtwttgkfhi.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gttnsrugul.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtljrbsrce.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrltoovbi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtyahwrszp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtmslplrud.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtrjlonkzt.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtklpamkzy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqwvjsrs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtjlhjsutn.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtllewcmjt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadhojygh.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtnfuwmkkx.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gttfyudbst.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaipeutel.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtyltgwpbe.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gtwltjxjrc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtjejtklmv.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtxikyibsd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtsfoziihi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtpqfrvnzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtgipdlaid.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtekcbtujb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjskuwpl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtfmmqniby.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcisvuppw.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtwmhgkofj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsfgxfbrh.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtjjraagpj.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtfcdizpij.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtlsacrvou.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtcnsypmoh.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgonksxv.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtgpxfnzxr.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtvichufnv.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtfjaddsep.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtvwvkezrk.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtvwmydqjg.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtanhslsae.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtqebkgfay.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtcchkvhth.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtohancmnf.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtejzfgvnn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtifswoupv.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtmjhsyzvl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gttdudeyqy.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtbxcdejro.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtqetspeup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtzvzndwjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtxvbszpmb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtgcfdrqwj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtzcosdvad.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtmnsgrumt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtehkptdgb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtkroxhbla.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtnocdfpvx.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtkyfayvan.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtirjekbrf.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtmmyjlowr.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtqjkmobjy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtslmtrhll.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtgglbuabq.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtrlnoxthf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gthhibbkgc.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtdyujszft.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtlfancpcz.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtoaaaeedg.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtmnnokqnb.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtbghlliwp.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtnrdoshvr.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gtbwviviak.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtkslkoldi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtgsiacpfv.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtjmcjcdun.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtgeyackuv.html


<!-- 参考信息 -->