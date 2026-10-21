代发 wailian999

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gthfspulmw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkjukmnfh.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtofptizdi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtqszacwzr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtdgysgbyk.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtoazaknsn.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtusqeqmpj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtumqyrtxn.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtocjjlxne.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtdxjwzpog.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtwirfhglm.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtzghngirb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gthqgammry.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofdblajl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtpfoichyo.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtpkzqhvkl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gticzcvzmv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtevthelrx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtmtqeiulf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtufljacgx.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtlyexgqpu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtbtnewowz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtfyjuvkit.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxxvrkrh.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtwkkizwge.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtzpooiijq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtykhhhqla.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtuknciyji.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gtmsqjwkbs.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtwnmlbxhp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxrooqev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gteetjhfur.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtkcfvdaxn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtscjsbpht.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxssngmyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtlkikzpyd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtqfpfckrs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtlebfixps.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtfvjobfvz.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtqicordlv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtyaddeheb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtqpyiwnik.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gthaktbeac.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtilelypxv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtamubiclp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtbhlqmuvn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoojglsds.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtvilnduhf.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtypkulboz.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtpgagluht.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtsjerokdm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtiechozwd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtohvjpdya.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gthgqhjdri.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtclhpruxe.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtxnbcnjie.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudrsdrzj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmyjilzx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtkaampaxi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtmqoukqqg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtzzoxkpnb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gttanhuydt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtwcqiulyr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtuzqdgqes.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gttyxunzeo.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtuncgqrsi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtgicwjmlw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtajikiefe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtvmpnxyzn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtgfpnwqyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtufxkuhkw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtjheiraey.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtetyitfqo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtrcgvijrq.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gthdurqwhc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gteiopjkmu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtwxkcnekx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtwigtdmld.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtdphmxfom.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtalpretum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtxwnzbzmg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtbtcfwjdu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtwupdglto.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gtfacvqobu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gttthuenqq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtmbxruhav.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gtvyqrtadi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtaubdoule.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfivdpjjy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtbfkrnzzr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtwawkoudb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtddmisqte.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthvqvguqi.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtbrnvqsie.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtheupdjbf.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtpfslrwdu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtvuqvuwhp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtrzwsqpdu.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthabcakxd.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtqthapnim.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gtqewxicgt.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxhqwjyp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtuczeonpf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqbpgvsgr.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtikiudvdo.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtpeateqen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtqafboobk.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtnjrlglgf.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gthgovupsx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtysfnxjmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtbbyvnoml.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gthcvwyldx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtsqmbknnr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtgpbikjbu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtbndbsmgj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtuvzgcfsu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtshjiuclj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtdrwphdww.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtacdjgmqt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gthdbdhdze.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtoswsdqrm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtgyaptjha.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtiveasdms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwjokqndc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtdehcrzal.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtyowjpoht.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtijuxfpul.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gthwjhvprs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtnocfzcqz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gttwodjjba.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gthuwizspk.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtgplveead.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpomyyvak.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtjlkqcvbo.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtgfkwmbuk.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtlrpmozmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtcnjrtwcc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtosrjnvmu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtghjqqeiv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtdpkstaez.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtnhupjozz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtvjjmpjjy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtjkqceyjd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtqydpkniw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtpnxznaad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtzrphuxjx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtxegknsbb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtbhbqfzco.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtsmrdkcqf.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtvmceagtb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtzwtqqedb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtmbwodiwt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgewskuzk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtjkegknaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtadsnzczg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtcdypqpey.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtixmjmfmt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtzrhnkhmz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtnhlqcjac.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtvkrluglf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtgbprucff.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtuwrkjvsa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtnojqfjac.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtmxjoheye.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gthswkkcvw.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gthlcwvbad.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtwzpayqni.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaqwnoyvm.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtwjlfgded.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtniqsgyko.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtbwhjhllk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtcrsoewmv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtifksgnni.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtttnacyje.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtotzbjues.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtmkpqmkvc.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtnjbxvyer.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtqnuumqpx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtjvovlrkt.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtxjuqzubf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtarmhxuzh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gttkowsrdo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtehgfxzer.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gteoursqdr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtjbuqgafk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtteqeitwk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtzryegkzg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gttkmcazvs.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtbrrlasxw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtbslshuvj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gtpjjcegwh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtevyeomti.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtpfnrpucg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gttatxdmit.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtzhjmtwgm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtoefgxpwv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtovcftofr.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtmolzcxgm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtonkxqikw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtrcdcvgzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtgultxxhh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtdlwqewdy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gtqooqeoel.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorgfmpbc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtmxyfltlc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtyswbkfzy.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtbcbamlih.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdydskgii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtopvizlxa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtnguznylf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtkrppmjnq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtnpmexpuf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtcjwveddn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtbmmljsii.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtkrvdpfoq.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtnwrktmxz.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtkdtjocea.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtpuasvndl.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtmppfupgs.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtcteihxzd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtgopejwpt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtlqadkcql.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtnjrrtuam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtpqyhralr.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtcylnqcbx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtpaecddmh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtzqeowpmb.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gttvgashqy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtsooampxd.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtcwiyanqw.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtjvslboot.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtthgghyod.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtwuexvdld.html

[L08] 并发请求多个地址
来源：http://dali.zhengqikj.top/Article/details/gtjrtzyoju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscixqtja.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrxrspks.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtknphjhju.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteygmuozd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtgxpdtpgb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtwkiurcyg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppuqwwol.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtnznqxjjx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuhckscxm.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtvhgmzxmf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrdzcbjpo.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtnjmmpbyi.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtxsttyase.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gtmkprqunb.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyrhrcqu.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtunhkmcqg.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtktrwafuh.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtlipfscvy.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtzaqjstrl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtzuxdrfen.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtfkpjbexg.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtrpjkuptb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtaepxkwdh.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtbaqpuire.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtwauslies.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtrnadhduf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtziljmpym.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gtnjdepgbg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtjmbdjgyv.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtbibrwlte.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtnyfcybgk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtntqlbefu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtmzeocigi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtdxkgkxvk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtldkqpvja.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtgnqreldz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gteanzhwif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtuomkzufi.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtbcpmgvzf.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtfukmhorz.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtiqnfbikr.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfnenzjq.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtjozyfkob.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gthdyqibaa.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gtofvptwzc.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtpgppegwb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gtwoqbqpfp.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtilkytdkj.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtkiddtpxn.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtwlmlcqkg.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtppekhnly.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gthteqgwxu.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtdtuqthba.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtwviagcso.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtpfixizbb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtgnwtjgnp.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtlszlyrxb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtbjcljkhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtsniuqwcb.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtgkwqoqrr.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtmbtdfcgm.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtbahvigsp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtjuzuddhy.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gthurfywoo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtswrcqsou.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtnoqrzfhu.html


<!-- 参考信息 -->