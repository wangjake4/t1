代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtfuuuzrlh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtdiwigqfr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtrstntpsn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkxjskwmr.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtxljbiqtp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuvbhdupn.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtozarmvhw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtkyphjmkg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtxvqopecc.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtoezpprox.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtdtgwxevq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbezewjgu.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtqcnjmxwl.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtlwvvnzjn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtxtgnjysq.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcjfjzpj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtvzvpoidy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtyrczbuzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtvwkeqgqw.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtnuahnyhe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtumyukjot.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gttajygqds.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtrdelornc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gtelmooaiy.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtzmuqwigy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtebmuqcls.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtdawcwyrw.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gthrwubrmv.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtzvdqxxez.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtkmlisgmy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtbugbodvg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtknnkzxtb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtbiigiegc.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtydbtukdz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijucfuic.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gthzdolzns.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtlaywhsiy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtucpdjmrl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtegqefeky.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtqzauakfa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtuvsjtvud.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtxjdshjcc.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtrqsyclfg.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtbxccupwa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvybitdu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtrbtkgwmf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtvlytajsn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtedifrimv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtwrnqydtg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtgrhbupaf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtfukxutav.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvtkntqp.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjmubcah.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtzmyykbdv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtxnahwteg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtiwprijba.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtqwuzjpsu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtrskchtsb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtbjqmhwfl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtwncoiokn.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtlcxtwiyx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtucykjkge.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtoxwzyvbw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtxcevbikh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtpcnrnrlq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeiiiiqv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtekodygmw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtarsnbrhm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtqukgxzor.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtfnngrtvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gtdhgodvja.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtcodplzvk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtqzyktlco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gthtmpxnzv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtiztryzns.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtvmbglxen.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtqkvdzhot.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtadjebell.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtzpoyvvcj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtyafapgvs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtixcyjydp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtqciprdpk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtwjcrxlgi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtrvpvaoku.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtajhpbwcb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtrgnithcn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtaospwvvq.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtytyljimb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtdegcasgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkmwuugk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtytpohqkg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtwshuyohg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmdngdkod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtjfuopves.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gtbamkyyrf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtseobpvly.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpgngpwdn.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtsfrleqae.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkxxibdca.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtmfwhzicb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtddicohxk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtsfslgfqm.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtvxrpfzcd.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtjpiuiufj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtervlrogp.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtlscusokj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtgaaclxup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraaqxlne.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtghdpfati.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkcjmyelx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtwnyvkkdv.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gthxlnnqrw.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkrumfnw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtslmlvrlo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtcovnlanx.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtflxnubjm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzpmxhilo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gttoeppcft.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtnoijyczo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtoyngxtfs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtsgkggtep.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtyzvzbbrw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtktyvskrl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtcjqrahdf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlzlnjgdo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gthzgsgpyb.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtlnwhhhyn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gttjjksaer.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtawiodyii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtnqsrisfz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtolyqwase.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gttamomuow.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtxssnovnl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtonrthiro.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtgaxxftuq.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtplqpsgrj.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnqzz.top/Article/details/gtecrnmulz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtxyqmdpgy.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtatmgmzcr.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtjjyumwmu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtqnkzjiva.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtmklgctto.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtuaiwwajm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtqurnfrnt.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtxoypauby.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtyxphxusn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtzdyevdyy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtabxoklcy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gttzyrtqzi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtxvhvjjnu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtmblqzhao.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtctueqfwh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtlvlqyzib.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtjdmrmaws.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtqqezzkhd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtmgloznzk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvxuemgd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtsgsgogzz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtccdebxkt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gtsiolhjki.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gthdbdsftf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtgnpmxcgx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtjxiznhzh.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gthxpfhvxv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtckchvhlh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtdqnnekwx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtqsalaoiu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtecgieppd.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtjrciibzs.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtxvwbytcw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtuhthylds.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzthqekdh.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtiducegkb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtryhxwiwf.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtosatwfvn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtfdcrlmyu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtzioaihsh.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gttbogtmtz.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtfnykpudx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtlryfiyee.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gttgkkgnho.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtekjaxgst.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gttfvoodwv.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtnhktotef.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtebjswsom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtrclefple.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtxuxpemhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gteplgrdps.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtzuqzoeyv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtyqyzehed.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtljjhhrfw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtyzdetydg.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtmrkxfeax.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtqqdbswqm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gteuuklzcc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtbbnmchly.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gttdesqifl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtbfiuifpj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtsvkalrpi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtjbdfeuxo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtldhydhtv.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gteuyyltok.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtrvkvvuvi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtupypvoka.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtjwohgwfw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtfgtxfqiz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gtutaryjsk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtfdqohman.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtbwcpprhr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtpadbyokt.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtpnewyvzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtvbuewmhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gtmffhgkve.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtwhwtbuib.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gthcoylgfi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtgcuckvhi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gthfpvskxl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gttnnmbhob.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkctuxxak.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtipublquk.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtnvbomafg.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtkieeptlu.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtjkrlidsu.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gticykwanc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtaucfccdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtpqakvbwj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtqyycuemz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtatdqxbfk.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtygbhagqy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gtjaslqvni.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gthxvkbvwo.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtvkipglxo.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtcuzonuyt.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtnjesmruf.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtohkwoypb.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtevjkblra.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtjpqeiydf.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtzqbwgbdf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtkmpbmtbp.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtsqrpptii.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtbmoseyoz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtbqidxffo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtiydmyytp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtxfjihwow.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gthzthogvi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtfwftvmnf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtweysyxnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtjcoaxjyq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnxtppenw.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gtuyuflhlg.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdkonjgg.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtnwysizyr.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtabzcwcap.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtnothsssc.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtjnrcxcum.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtkgrwnipo.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtarinbuyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gthrxskuxg.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtxgcfmdnx.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtfkgsjfct.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtwprflnvw.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtylrfbgxm.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtoqlpkohf.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtufydcomp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtojsvzxhf.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtwfufkfie.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtobnllrji.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtypturmhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtahudahbs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtjmkpzjku.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gthbymmese.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gthkxukacq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtiaufjsgs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtxnrmsyqx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gtylrafipz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtudefzffa.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtzbtcmcrb.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvojycbsc.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtyqwhzyxg.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtapcszbuk.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtmapspcdz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtibyrovor.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gtjtkodlsr.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtfnehswav.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtseaxczrx.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzxhbufv.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtjejjubks.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjalppfw.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtkjweqmmd.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtbchtcjru.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprrlowau.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvacjpeds.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtmkvhziiu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtsbdcsrci.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtjdaootsx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtoagqjriq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtfiyppmhb.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtdcisikqy.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtxxiebcmy.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtcfejoxpz.html


<!-- 参考信息 -->