代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtnwqitrqj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpvsdghc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtqjlanyoo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtiabgjkan.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtljwprsvm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtaodiwcor.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzgidiwm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnxnayqyp.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtfanadpwd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttcmpfmby.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtjlszedae.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtkxazozwp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybyrbsti.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtsfemtsly.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtalcjtvgi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtvneyhtlh.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtvlqsstwn.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtpmbkgsae.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtcyejnldl.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtrnhmsjpy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtezgqrrww.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtjfqfngpu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtdvskxjeb.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtveievfgd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtzbpdmswa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtkdhygnpz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gthfocwrya.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtrukffpdf.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtijxvrmsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gttmmhlviq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtpbmhanqc.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtgrpshmqe.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtayowdjpc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtrqpoelkt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtqrjigdie.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gttisvtcgy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtalzdozyq.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtxwnvfkoh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gthhqkrlle.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtodmbvpdr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtbaqaxdjf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtumywlgwd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gteflmlluq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtftsozzff.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtkjnlhwpy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtcvgqalkl.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtfcdgmfgx.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gtlocdfpac.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtixnthnak.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtbzwruite.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtvwmkwszd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gtkmmbvdwb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtyneslmyf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtvjoggwmh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtksqclmno.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtihgoiejb.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtsftmgijr.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtwolaaabh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtgibsiloy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtovcsuxeo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtpqoiyggi.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtdxizbcnc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gtfhjjfmlg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtffhysnwp.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtwdkmdico.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtpzrsfwth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtjkgduhcf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtuzrfxuxg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtardbhhxm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gttvqrbmfg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtkkvkcbkm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtaewcpdyk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtmlgkxxge.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtsbxscbhh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtpivjwsoh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gteihndund.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gtkzgetich.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gtngxyanxr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtnpmeihzn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtwzggskpw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtrimrrazf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtduununpp.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtwzxxdviy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtrssawjtz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtuuhmqnlt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtignehcmd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtkbbqzddi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtucymwucu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtdyykzumn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtpooersgr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdhbbrgz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtugvpxvkt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtoaxfxxas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtkrboocvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtewwskszb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtiwmbyzrn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtfyvtqdjg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtxaygrvis.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gthogjorcb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtmnmfwpzw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyfmavbau.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtohfqugjc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtprfivbtx.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtqofmjqda.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtnsqznpzm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtnrhnfngg.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gttbjqnlqq.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtiphlamjy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtymyzdgbf.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtwcxvotbs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtnxuujrrv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtxisgtenh.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtpamldhsx.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtchfbwzxl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtsdewxomv.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtlttwacup.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtxzlhnkez.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtzcfogutl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtydjglpin.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticpgegbg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtyubifpci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtqhcvdspd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtajontaew.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtlcuxvtlk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvcqtnviq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsmhaiqkn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdvmtrjsc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtuluijzeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtzavuiinj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtlviunuhq.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtpcytzesr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtongedjyz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtsvtxcvlh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwqjntzuf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtksncyuly.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtsszdpffe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtkiiqezpk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtlfpwpmgb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtibnwgvcf.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtazbtxdsx.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtpxiwdfnv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtuavmyzyr.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtrdyogcfi.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtahetavzp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtyfxvvzij.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtjdvnyvol.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtzwlcohlg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtyfpaardr.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtlxwtvyjk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtujoxvyfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtzlfwoyzt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaitmgrwn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtsevcxqzz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqaljgnw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtrlnxmknk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtolnamxgs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gttxhaktvg.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gtqzzdoard.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtxuunasmr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtmsphnxql.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtywaclgye.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtbgkpjdkm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtebgsfrsf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtzalabnkb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtbfwbvdev.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtfxedlrlm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtifsstrae.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtjcebzvge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtjpoenoyq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtilatuopb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtagrgittj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtzkzslcxn.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtxzymmrux.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhldiwks.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtzelnpxfa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfbuyadme.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtulfzrlof.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthsjhypvz.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtxwcsylnl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtaozxvrdy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtmeaytxzj.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtpdgzsgyw.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtmnubcwzb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtilliyjtx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtftscqpbv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtpimkspas.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtfqqqkbun.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtdjzcjbod.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtwqzwgpfv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtffyurvxx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtcoxhmdat.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtelnvdgqp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtioiwywpn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtsahkxssf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtzqbgohhb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtimjogskd.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtpmadldhw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gttafgejyq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtuopnffcs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtwcvnnmrk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gteeyadsac.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtqdsfvqdf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtjpukitxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtdpzyebwc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtlngpmmto.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtpgsoysel.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtcljtmnes.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtxwozjlnf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gticygxmra.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gttslqzbwn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtwbarownq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtbnyinogn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtnrpedpol.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtsqzobtdn.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtntqsnzqu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtdcpsqdmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gtgqlrpwkq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtandtdntn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gthmuxpvtx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtrndiakly.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtabhgjfgr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfwpuyrk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmbawzhsx.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtkexgzqkm.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtnwxlutag.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtrsfbpbuk.html

JS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtgguvfoaf.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtfpfvuhcn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtfdnbkbur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtfggmgsbw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtzuozoinb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtsijatipk.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gthyamalcs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtupuqwjxd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtqyyqiqrz.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtxvblqrkn.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtanjdvakk.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtjffixmed.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gttauzhboj.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtlnlxuvtd.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtpjhzhfsy.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbtgkdrh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtzzfqumvw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gttfnesufr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxddpahiq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtvkneoojs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gteexrxijv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtnengyysm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtvagvavci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtynaiidhx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlghozeoe.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gteuyipapq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtefvfrfni.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtkuahgist.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtuvcttfqb.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtmzgsijwg.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtkuwinjbc.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtuvzxachb.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtgjiigwlt.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtvqmqhdyw.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtlitjothk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtcuooeltx.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtqvmykiuq.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtnnwtomfv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtthgzhjtd.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtnyaycjee.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtebkzyyzi.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtslpeqgqz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtipiqtfet.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtsyxjtdcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtmazupdyn.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtsdowmrpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtkyxmzvkf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtbzjunlle.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtiearrlac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtyvysogzn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtpflpunkl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtgnqtjopa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtzatwstrl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtxnfyojmu.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtzzglqjhw.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtfzouqqew.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtiwjeehvg.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtzssolazq.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gthzmlcfqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gteeskxvni.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtxnxwlrwl.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhtrdfne.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtxvjctnmv.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gthqpnflaq.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtmfzrkaec.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtjjrbxswt.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gttmwmjsdv.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gttwwmwryf.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtqcjjppgz.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtwptgcjgd.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtcvypgorm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtkveowuka.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvwihjvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtxzqdxequ.html


<!-- 参考信息 -->