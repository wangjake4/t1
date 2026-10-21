代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtykliauyw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtzuzwdwjf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtebfwisde.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyastnjdr.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtpellwipu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqilmxeub.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtdbvanlqo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtcblnwxsj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtdzmfualz.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtwirdftud.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gthtkmntwa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtfsreyeva.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gttemodnwb.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gthsysxzgn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtgvtlpmqi.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtkozexjug.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtxrurralj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gttcqvljvd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtiiiqpexl.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtvwkbaxcc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtrrwhsxfs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtcostyehu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gthptvmdgq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtawlvtwys.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtrdatpfog.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtjflcdrtu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtsikgtelk.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtjupugmci.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtctsniljc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtsbwykffe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtuznrstyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtdkssjcsk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtipheaoag.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gthjofnmuh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtdhpesqpq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtobqwrmox.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtvwpbqsrz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtocfvxnnh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzkhandx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxoqnihn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtsjlxjisl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtiqyiouqd.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtxktgismz.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtgzbhyrzk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtyetdljfo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtlpnxjzwc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtbbnsbwhk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtqgjxquby.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtwskrqbqq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gtewpjznji.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtcmotisim.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtohxfgfxo.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtbtkhdvas.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtmbynwrpo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtjxpjzwux.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqlagllg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbthjyesq.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtgwojtkwp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gteflyqpmy.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gtnbjptqxg.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtxbfcnrei.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtppuogjah.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtelvkmunv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjxsjtwy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtcdfnhzng.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtekamruno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtphgpyqgw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtlwzwzimh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtdwagfgst.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtaxwrlnnv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpmncyzu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtxskhjewh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtnjkmrxmb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gthstlofqs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtseebkhza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtrmucvexc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gttgngoxwn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtlvmvxdfm.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gttnivjyel.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtxkkuczkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtknkvozvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtcrtgrusn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtszwaihda.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtqhvwwpde.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtnfwhsbrh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtxuqsywek.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtmwsxuwmt.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtlrbiqmrn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtnhnvynoq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtqgzesqyg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtiizwbjte.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtbyyikegw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtrhqrtjlj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtdmsmovxa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtioyowwie.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhqwpafs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjhjvzqby.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtpivcxgpu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmpaidayk.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtiznelbua.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtgjfqpxzj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gttkyphofp.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtvptcvooc.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttuxkqdav.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtnmuqxzhv.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtlcnmxwng.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtsvebmdxf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtpwcanlwf.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtlmmqlovv.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtbdyjwquk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtzkrptbjn.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsmwvzjfn.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtanmmaqqv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtgbcqdeus.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtbdyydnkd.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtmrggultq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtoqlcknhw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gtwfqiksbz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtfsjwwgyd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtqdgmrbio.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtoitspoyf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtrsqbpphj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gteplcdguo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhkaorub.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtviknwqmf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtnezwtpqb.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtwsrgxnys.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtnrbzphbj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtvrhgtxbb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtbrvwkihj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtllxvzenr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtgfhfuluf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtxqnxyhht.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtelcoewub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtclsxxwfn.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtuadloioo.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gthfieruff.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtzekcppjd.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtnapddjhn.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtjyuzbsvs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgeasivz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gttdtekfad.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtydmvmlam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gtwoyuhbuu.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtjyiaedjb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gteenpgmhx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtbajhirbk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtefeteilt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtlfjctuse.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtyjvpydiy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gttcgmmchj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtxlsolmzm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtpjdncbti.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtghmxmajh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtalfemzpc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtlgrbaepk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtyzjytlxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtueoeluve.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gteglprujd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtzskfpwwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtceviuiqv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtexfkesez.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtwlncibpo.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtcnuketsx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtiheyqbfb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gthutbpwue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtytezfaty.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtzecbsjmg.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtvqsplous.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtailyogvk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtthsbzcbi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqlykbmpu.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtxnygarwo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtioeesijn.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gthjccwcxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtaayqkojb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtbpaabrxu.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtvktdhmla.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtgqzfiayu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtwbgbauhl.html

Go:   resp, err := http.Get(url)
来源：http://dali.feifeiyinyue.top/Article/details/gthvdbctls.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtjbpkisgy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtjnbppxhk.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtfpxsehgi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtjqnwnfnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtcenqxbyh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtqzfjpomh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtjzdfnjkd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtnadkhxni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtgtsfqihf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtrojktvwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtmbktrcyl.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtudrmblcu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gthkkimhxl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtwfxzcgkv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtdtsllqxo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtmrfgihis.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtgzqdpnba.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtpirxbpei.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtplkenxrg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqemksjr.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtkhmjegxz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtviluhbpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtpjbtwkeo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtheoadsit.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfzdyfad.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtgscngrdf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtfosezpnz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtsmcaxjta.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gttayjdxbm.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gthyzkvvrw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gturjfjopv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtctyijpig.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gthmoourls.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gthrhfjxba.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtukyrfidr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gthpdpczdx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gtwibwngep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfwhgwtsv.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtfmcigxqq.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtimzcreha.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtdxjxeuin.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtnnvrjdxq.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtykzhjetz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtboljkzta.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttemlzlgf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtqnghgtvf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtpkylqrpi.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtbapmjwwh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtlbgpuioq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpjykaeg.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtydmcccec.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtoexnyiev.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtuvovjkht.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtnbdqhncz.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtjocilysp.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtbpjcspqz.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gttgqpwmiv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgfzy.top/Article/details/gtzopbyaiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtgzygkkfp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gteefhanii.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtneojagcy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtausmjpvc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtqrvwfpyi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtmmtvxcdt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtjlnpursy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqkwlzvgp.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtwmndvbzf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpsmkupxu.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtjooekjzz.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtbkyrzabd.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gtbbczzdxx.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gthbajmzdm.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtzoqroyzv.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gttwetokou.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtglixfxvk.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtckmesplc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtporritko.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtbspkjqgt.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtkjdckfos.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gttatduuwm.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gthzwqxamk.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gttcqdrsgp.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtmdvswubf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtkkvrlexv.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtzzbubuac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtsmvcuixz.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gtditmlmac.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtunffbssw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtwfzooxtt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtcebueoue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtvkhxeans.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtbrjnkvtf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtsoswptgd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtuykejhjd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtfufwwbna.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtbvyvygng.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtthqeaymy.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtzlfwjvyn.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtuunpnezy.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtrohvirpf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtvrnjasqn.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtgzqmqazk.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtfywjrocq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gtzlchsovq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtvmcdffwu.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gttoiymvjc.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtqddxqsmd.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtorixlhny.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtlzbjaewk.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtppwayxnm.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtzzuuosmf.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtjhdtuiki.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtwybgvije.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gtcqjgykkj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtiefebzzz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtkabkfqow.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtovbmicyz.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtgqddwpxu.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtlhkoiypy.html


<!-- 参考信息 -->