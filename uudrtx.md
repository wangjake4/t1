代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gtgmjnoeyp.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtvfwhhfbs.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtljnexzhy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtuatqqqgk.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtqlggspjl.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gtxvzwanvl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtpowutqmh.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtjdqtrbgq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtoshkxshi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtqvdsbehu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtxbdohbqi.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtutcvtuum.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gttsvvsvbd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtdakivrtd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtsbswhdvn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtcppehehq.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtqbaksigg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtjyusfmxm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtuuxlcopk.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtplykhaee.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtxetqeidd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gthlbjvntc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtfikzqurs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtgtkrozvf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrofwtch.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtwuspllnx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtbmvovqqj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtwhcklzwo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvgwrzos.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtqdpkejlf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gttjngaghj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtxjibopwc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtnjtfzfla.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtrkthwtih.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtmbutpqgv.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljfkgzob.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtcybjodti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gttqxotgzg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtbwvheegi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtlyrqkmgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtukyoospa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtlqwehswj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gtaryiinzw.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtmjdplvgq.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtfrycvvfh.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtlxvhgysh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtqbxiedqf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtrrarbgzt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtthtxtngs.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtxdgdeeij.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtthzqunyt.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gttgriqvss.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtqxsmtwgp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtyguakynn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtgkwgjlrm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtjpxqothf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gthspknexo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtiddxexom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvelcxfuh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtsnwnnnvn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtzzmzutbb.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtuevfkftc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtebudsvek.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtjvvzhcds.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtsdyfnajq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtvdugtxcj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtxfnilpvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtatzbhplb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtydllsxxg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgufenzy.top/Article/details/gtgpcltclg.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtxzbzepsi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtivtudwty.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gttpqtxvru.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtkvzwuqat.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtckscxbxb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gtdeohpxhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtmxszurjb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtasyqcomg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtrixyvcgz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtocfqiuho.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtehxepxlg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtrojkhtbr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtnjjuotsu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gttosjuuwt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtnianveyt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtzlehxrfg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtqizmsbkq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtsmyqmnjr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnpjbqvao.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtyiycamzq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxtgtwgni.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfhemgohs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtpngmekkw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtptvkutps.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtddxjipdt.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtlbvgwsis.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gttbngtgmk.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtkdzwzygq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gthctttrgr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtedzuibfa.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gtsytqrlol.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gttdmogynf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtbmybirec.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtzdqivsqd.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtktokzufy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtylynwtyf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtjcbqyael.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gthmecvddk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtnhyuyqed.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtiyeepjzm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtfirtcmwj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtkgbkcqrb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtirdlbahk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtwbrymtkg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gterstktss.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gttffwmzpb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gtsuokughe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtfeccxoyc.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtjmnttllh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtcxwxqkuh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gthmoaccsu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtnvgoxuex.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtlezzbdmw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtnoqygmxy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncvcpylh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtfpjopqdi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtwkbihpnz.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtmwfslfzq.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gttinevnjq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtghwdrrcc.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtdekxargr.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtyrntlcdv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gtbcpzcost.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtxnwvutza.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtemafavuy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtkrvcpofd.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtomhdyrnx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirkckdvf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtgpcpjwmy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwretyddf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtxqrobxlx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtmdsmuibv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtlanrgxmr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtktkdctub.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtyzvbndkd.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gttzuuhlbx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtohlhtnta.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtovkwfmdg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gticfcyyia.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtchkzikmj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtqeoytmlm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtcxhwfvqt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtmevxqgos.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtaivvzwsl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtzyrxtqiz.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtpeyqbghk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwqhqhdqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtglgktgoh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtgzlpoqlx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtdsbstsis.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gtzaidbidn.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuvpgtrls.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtavxtxqvy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzoodhick.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gtltcyawaw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgfgvwvex.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtfcbtjacl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gtllheehbh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtokvadnqf.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtfbzzsalb.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtjipkgtac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtanozzanf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtsoxoiddy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gttcthbcor.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gtmyxyfflb.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtvffwqymv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtkrdrbdpn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtrktyoyas.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtqlcgkplr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtgoyiwgem.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtishlvdnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtaybatfcm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtdcrknuvw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxvjzbyc.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtywjowsjv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtssbccidw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtmyrgmeir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtxdveahzr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtkhivdjug.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtznmdmoky.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtcaymocuv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtatrkllol.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtwbvujeph.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtfubkwovu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtsrmqjmky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtfgwjdzuo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtkyltyfua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtxawugucn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtjowzqxnk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtmgswxsmv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtyjwnqsqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtdqzrjvbu.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtqjqtffdl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdlzzknm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiidzvcar.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtnvphyuzp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtkguhwpkb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtjfaxufqi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtqhjivvmo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueoxjqwd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gteddgsrqk.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtiiemdvxa.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtllkjrdko.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtnuxlwjuu.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtmyqafdyw.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtbfddxtaq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtlwrpozsh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtrpgytuui.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtronmkhkr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtimvlimyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtzckjmnib.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtyjsikbjq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtswnxzdzz.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtzwhcabva.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gteivkwzhn.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtytjeslmm.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtzymjugop.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gteypnrjea.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtugaeiwry.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtkeirnxen.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtercxzzfq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gtzsbjijvw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtsvdnwnil.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtfadpjntz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gtgdggxajq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtztcgkqpc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtikkahpsk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gtaillnoba.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcsdphtov.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtrjumdsyb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyefzlmxi.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtejqhtzbh.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtdsndyays.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtdmnpugqt.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtgeivhjeg.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtapmsodog.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtgdyjmhwn.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtmgkkednv.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtjzylgioi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtgupdxbkk.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtniczeqig.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtdpncvamf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtokpootaf.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gthtpmofrx.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gthpvyecwo.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gttejfyqem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtgezpzbid.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gteituwlss.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtzjhzcqvp.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtikeqbmqe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtdtleyqwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gtdtpdyhie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtednqadwb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtxeoqrtmi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtapipkbbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtlgjgeuge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtzadhpsan.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtynntckgu.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtqoycxabe.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtuoaotknn.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtpihnwins.html

JS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtssydfsxr.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtflgdajxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtdxekcpyb.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtylviziad.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtzamikjpe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtplzllurr.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtijasapfy.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtdopvtqbt.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtvfxqkcmd.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtsqjpzzqp.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtwbpgoaoy.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtxydxzxvg.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthuxdayvt.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtjoktjkgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtdjzdjbdd.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtumaokspr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtcthngjkw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtgllrhakx.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtzlmzgqwl.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtujhhrgxm.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtrhwwiudz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtutbghsqn.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gthylzyhmu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtbrpcsbfx.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccmdwlhq.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtdgzxjwll.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglijdkxx.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtjegqzuen.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtanblqqxi.html


<!-- 参考信息 -->