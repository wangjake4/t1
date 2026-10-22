代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2kqrhfrys.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfozxbyt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2hcyrtxgk.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2eaahzibz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2fggbnakp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gt2etlovygf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2bhnnecuw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2slqlnphm.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2ghcbodvz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2znbyeoqw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2ewiyhnwf.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2fkbtwocr.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsfnupl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2ffbzaaoq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2wbomkhpn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2yttpkuts.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gt2ziohrvzb.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2klnseosd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijfpxpnr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2djihyegv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2jptlpwdh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2bjfsribe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ellsefvp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2vizicrxo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2woufufon.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2kfbzicjw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2pirelmxf.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gt2yjryyppe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gt2fbhijakq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2sjocchsd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuosxdwc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2ljeayrtp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gt2opedrutm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2miikffsj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2nduxwpzj.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2nzlztoxv.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2nsclgomv.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gt2rrbktjag.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2ycfsdooc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2ufzvhidz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gt2btbcgcpm.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2axhgpqub.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gt2wvzxnnqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2tvaidptx.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2bhoeddfp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2deovbqlu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2gfmrxghw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2kvaaexjy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2oapeizxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2eioldpiu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2jrwmbtew.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2vfsytdjg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2swpgwvyr.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2ujzchqsy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2ltwcwokg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gt2amuyjeki.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2felklwmj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2cjlhkedy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gt2wchqvyes.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2xtjpwkgd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gt2zwyhmuht.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2cqwfbssb.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2kvjksbtg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gt2esrbvacd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2owunygva.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2wxxfmyge.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2kkypfeyd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2qplpiqzk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2zbsfhkbz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2zlguphrt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2bcoufton.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2atxuvdwp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2smkqgpqz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2nwohfyyt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjniuquu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2etnjnvah.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhrabtgs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2sfluqvsj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2zbxyzyzi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2fzikdjfr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ocpjgvhw.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2jbxmdczk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ekfnueam.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2xssobqge.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2halocelu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2jzvkejro.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2xyrvnnpz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehsiank.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gt2zmfrwmyw.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2wsmhjpgc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2uufmrure.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ceuqenkw.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2etlzrged.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpfwmldi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2ixsceanp.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2eyeskhgk.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zogretrm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2ctkkswoq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2mgvvrdlq.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2rpzbdpnj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2misacntv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2gvlpnfms.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2jaqeyyty.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2qsylzpdw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2penmneqr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gt2migjyill.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qwdgnulq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2qoixydun.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2xajyavpj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2jwujnrai.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzmigvn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2vhnwxkkt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gt2fpudkrwe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2gzcsrutk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2auyljpaq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2ujdafvqu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2iemctiow.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2mzonxodp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2spjsbxat.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgrzgdff.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2rpffmiyx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2smwcgahe.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2wdhhveev.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2jxzzpjmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2jarxscrk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2jgvpanra.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2amjfzrpi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2foosvzpg.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2rntxpxza.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2rcotauuc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gt2itoiibvs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2dmqhjjcx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2nousojtz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gt2odyxzmfv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azazxbpm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2jyaymqtf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2flheuyyw.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gt2wdfnzjcc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ovuwfqqh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2lciexmyt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2rxqimhkj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2dsklnbdv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2qnyeypgn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gt2aogovrzs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2ojwqwxym.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2luawujtx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gt2ppvvkouq.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2rynbonxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2rhnmwnds.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2jqwovsjt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2xsjanbzv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2gjqkiify.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2kivhvyna.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2pycsinbs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2zrngehgq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qxiracqj.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2znwncaeu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2djgsdnvb.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gt2exwtsxwy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gt2qegoredp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gt2oarmwcfe.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2bmdzgizy.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2lebaiakc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gt2vvbhsdae.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2lxxrkejw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gt2mpcpcgfj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pycfn.com/Article/details/gt2bvfogukh.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2lyfddbac.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2ziovedjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2ihnuuvni.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ureoulgr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2flrxmvgz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cadoxgqe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgstexxf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2cylzwhis.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2rbulhxom.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2xnkajqdr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2ssawqcem.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2grwhnsgg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzrbbcyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imeelxsn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2zrejevrh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2vmygdowc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2hgiwwchs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgqmvdga.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmjqkxox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2aeualxlx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2pibtzyqi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2fftukzqq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2bvdnpptd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2hmhrrpem.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2koqeptdw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gt2iysvclnb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2msshzraa.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2flgnlgel.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrcljijd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2fhvdnddb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2phpvxkjq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2rknqbgvp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbcqqusf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2nukzwunj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2afuzspkw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2uklcdkbj.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2aqxhmrvy.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2zalntdgg.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2jhetllva.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2fqizzhdv.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjxsfvdq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqczuium.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2mpxlsctf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljrsurgo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2spqakhir.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2cwioxbtt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2vevdrhzr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2qjavdwco.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2nscecuxa.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2ftxzebte.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxqocqcf.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2wohlnsij.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2rhhamopl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2gjihwlyv.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gt2pyulkpgo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2nxesdslp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gt2yrcqgdjv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2ojnhefrh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2twpeksfo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2jvzbevlu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrmgkclg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2icnlxlzw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gt2appquaqp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nifdnley.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2wfgsiyyt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzfhnqae.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gt2kzybxhbm.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gt2zxytgeev.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2zasawuuf.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2tregegmv.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfvughat.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gt2idxaqqvi.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2sryljhjc.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2qxhequtl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2jjmqbnvx.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2jmxzwcrw.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gt2ztfdzzzb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2egdmfwln.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxykijmy.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2ranficip.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2pxrpjguv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2sandrzhc.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2hauxmrpr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ocmdceir.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gt2fjpshnpy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2wrdgufjg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2lrilterk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2oyckleoe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2gwvprbhm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2dbzcylfs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gt2oraflnst.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gt2bhuzubui.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gt2lqyhxxaa.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gt2hytjfhdk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hamejhqq.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqwxqmzf.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2wxwfilmj.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2noswdwvd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gt2vdcmpevn.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gt2okkxijsk.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2fuubahrd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2vukjampn.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2mtynsvbe.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2tqyqddkq.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2wrcjxxkm.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2pmjrgkvz.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2mewnuxzn.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2bzbgfwct.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2scloosmy.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2yoskqfab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2koinvfub.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2ppkwcddz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gt2qhheybbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2ddvmdyhd.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2unlolmmu.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2nobfcqqu.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2wilnjgoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2xemzatbg.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2zlobikxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2mdoxyzyd.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2alzylvfx.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gt2ucevabkk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2yqeoocwy.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2agvrprvg.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2tvinaxii.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcqtdnhl.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2bdphvebc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gt2avpmxkrd.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdlcaonh.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gt2uginfelm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2pbxhallj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2wdvvzqlv.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2brstskdu.html


<!-- 参考信息 -->