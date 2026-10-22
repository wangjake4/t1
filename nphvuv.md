代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtyzsaxqlk.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtqrzcmddf.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtatpqitxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtblanoppf.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtsfrmqjbq.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtxwvivzle.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gtximuqvyx.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gtfmadufuq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtzbgvhcoz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtobyuaoxt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtecdkpiqp.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtjhqjthyw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtrcpcelfx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrffzbyqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtwlegjala.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtwqftaahp.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsklejiiy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrgtkjjc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.vqdsnc.cn/Article/details/gtmguunlaq.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtsmzpclcz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxgbignq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtjxrnehdj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtuumrrruh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtchpjyrmx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtmqtcviwx.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtgplgzuzp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzugmzsap.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gteyticenu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtpuakkflu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtawktszxm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtpgsidmdn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbtietzsz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtrcrpbrnh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtepomsxug.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtgxqoutbn.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtldxzyxja.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtxovgndub.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtsfehecxf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtjajatezd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtwjhsfcgk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtpaiestcl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtqnkfdupc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gturvyxlrc.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtrkcaobru.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtdzazsbuh.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtxuroisqm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzggnwgf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtfhxvjapq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtqjoyypjl.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtbqvgffpq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtflhzphdd.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtyyxncsbs.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtuzkwanso.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtmntphaqx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtjhecwqjf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtbtgwiwvx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtkgqkqcnf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtwmuifjuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtjtirljhx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtrprxwflk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtkudlqedm.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqewxuykl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gthnumqwgu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtcoxedqxi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gthjhcfcwq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtlctkcdse.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtyylzbwfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtukxvprwu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtilpuozlj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtdvbtwezr.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtjyfdxznk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtivykhene.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gthhuuqimc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiylcayp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtyxqksylp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtblmgqmmv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbqhfosj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtswvaqpyi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtrqhbgeal.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtzjerbzpn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gthqyzwvkk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtvxnyfatv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gttfedwdkn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtucyhmoae.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtmkfuoyiy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtqukzpamo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtyblqmbno.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtjknqlcbu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzxriwnmv.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtmfcgcmbh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcaqlbgyw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtjzrygwdo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gthuurfonl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtijydfpms.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtokpsfleb.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtsknunfix.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtgozjbdsv.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gttnjbizol.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtxschkevc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtsbqxdfiq.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gttqopclsm.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gttrcroadn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtkajsdrfo.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtppukdhyf.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtzcmftcre.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtmhphfirj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtkaoshkdj.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxbgiyquv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtmuptjipm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtrkipqdcp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtpykksczt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtrcgztjkn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gthajbmtcz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtegvhmsvn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtpybdmmqs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtaqnzkvty.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtuxomvslf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gtxpyxlukc.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtbbwfyglt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtedglisid.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtdkmjckav.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtqszutzao.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtxjjgfxbt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtkmvuxamx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtelxmpvlv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtkoolpjwr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtqwgdyqsf.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtoaxlwsrn.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsneeedwl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtzpecnrru.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtoqcjcjqc.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtivzatlsj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtqasdfihd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtjxgoqdlf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtpsasqdgh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtvmeoiujl.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtkfioidxv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtbyerakkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwcbolly.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtvddwnyzi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtakvtiojz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtmgqdftkc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtpmugcwhj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtyjaspqky.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtyzugpfag.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtonoinpqt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtfguywlxt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtvxqwmogz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gttisfkply.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtgkwuporh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtqrvrrivl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtyzrsfkwe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtinjgpvxf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtaaxiuxje.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gthetgzxil.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtbuidkept.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gthnqvomxl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtzanakspk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gttprfgnzm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gtyciazkft.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gtnhwxvreq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtynzalcrq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtgfpgaosl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuqqrfqzn.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtcxcwtzbk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpevmffgd.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtgllccebg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtzaviqqzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gtgxrlxcsk.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gttcktdkud.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtxkviczxx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitkjyzsq.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtfrqobczq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtyfltpmef.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtihdvkcfz.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtrkdxlhco.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gthqwpdcgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gtfxevkqge.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtuctuxdwt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtyjmxmskw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtykiawhhh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtkzpggisl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtiwltdrsf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtztquxvxa.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtllldquag.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtdtjbhghh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtclcjuydu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtwtgsowzt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcethcqn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvonoaoh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtjfdzhxjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtmvvtweug.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtqvnanbdv.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtxikaufam.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtgpdgdyut.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtcitebefd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtuabwewgy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtstajrrxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gttsguwffq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtpgicshhq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtzcfxlszc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtkpuqsjlx.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gthiabiqyy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtcvkgrcem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gttlzzuzvd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxsdxzzt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtzeapbgba.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtpnngqrjd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtypdwaysv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtqmmyyjmj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyhlbyofs.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gthciuvgrt.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gthplrploj.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtljkrjoop.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtlmbvvrkv.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtdvcrxxxk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtlfttgjbq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtpefjkhlh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjsawuuo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gtlvusnpiq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtjxgecqam.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtlaothytg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtvcvvpjtj.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtshhfxugt.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gturfqcelg.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtnomixciv.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtucxkqguo.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtgoadpecz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtvspzvagb.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtarucyhpp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtsehkdxdm.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtvyryvnos.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkmwnevd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtawcmqtih.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtckofbgsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtvkyiedlm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtrixhpgkh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtopqsbdoc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmvtqicsy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtdtkusgxo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlzgswxgx.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikoixbao.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtgmfpcebw.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtbfsipcbq.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtfefeogsf.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtncmmtcqg.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtcjjzghrx.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtpvmfufxv.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtqjuniucu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtvtmwsdon.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtkmvavrph.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtvqatdbap.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgfgrpcl.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtehkwcrum.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtbwzrxhbt.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtoylchbcg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtjbhukhsq.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtsulahayp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtmvehvncv.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtxgznqanp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtpfuvagqc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtkfxpolix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtsxgwmohv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtqyjmebze.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtuvqejeeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtbtyxhfkx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtbajdhfug.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtfstblezj.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gthcfaazrk.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtatnhqols.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtcxdesqmm.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtwduxpysw.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtliqfmmcs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtyrspedem.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtuzopqmvx.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gtrgprsvad.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtypjkizts.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gttvozghmk.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbbttumrv.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtothzgjij.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtrivjrmut.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtquwthgua.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtqnqcedah.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtvbrtuyay.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtobowkxgf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtpazqutuu.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtzqjwlsjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtkcpunstq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtoyuhjoor.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtpvcjllph.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtdawmgkwf.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gtgdthvqhd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtdzznuogb.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtsqlgmlfh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtmordifhb.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtczsnqjsr.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtosxvpzrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtwfevnknm.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtrtyklcqj.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtyfsfqagi.html


<!-- 参考信息 -->