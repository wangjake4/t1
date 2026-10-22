代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtbwqdwwip.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtocumrbgj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtwqkdvgfc.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtusqkvxng.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtwrbqmkle.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtgalxgmhg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtjjhoebvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyfoagtb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtwzdutatg.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtxnisyihp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtlybrlomu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtvaxqxjxp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtzcwubaac.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtrrpjutlv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtbhswyshh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtvqqgzdhq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtpjakrosv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtnvcvzela.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtbjpmwgvm.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gthleghoor.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtaosgpeaf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtpsnlcopd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtiwimdfin.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtdaueqecm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtvgzvnrub.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtaklzfgtp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtjauqgjyx.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtyacckjcw.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtrgwcfcap.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczelrbiv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtdtztkkza.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtilsegyix.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtcyxwzftt.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtrumzjhbt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtsgssttaj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtqbyagauv.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtycuteewq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtrqswoxpf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtbdqzxcnh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtejszotlv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gthhwmnyjj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtihvfonob.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gttormsvcy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtnroioaqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtnlljisyh.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtfethbdre.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtwwkrucbo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtnwdyqfif.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtncqjxovp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtftaktzvx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtibygidtm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtttplvccw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtkkyqncdj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtqpvjbkmh.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gtufgpruiy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtqkqccaoz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtyrrcmvvy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtynyjfxzr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtcuxvpbqe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtiufxmhdo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtcgbkwtvy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtsbqdourb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gttselmrto.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtbrudjoma.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmusmgbw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtyoxypfjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtmgrklblp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gttqojspwb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtivmidext.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gteonidvci.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtdceztgxb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtfaltcesb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtigmczdkm.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtkznsftlx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvixvzgbz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gthvossbqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtjrkrrubx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtilayvfev.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtibpdkffj.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtqdgoalgt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtfqixmxed.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthuouccrs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtszaonmkt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtxovaqekt.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtdwvoytcz.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtelacqyfw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtrrxsqzad.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvaxgzmg.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtjqpcfktp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtnlyywokb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtwvlaadku.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdqglvpd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtlbzgpqxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtwyawmkdu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtkomleeib.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtcfbvrnbf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcryqynq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtquujyfjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwpbshkjm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gthzlnxlqt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthlypekxg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtakxhdcux.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtasfspwmp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnvuihnsd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gteysbdnna.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gteffpwwhs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtvxbuarcj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtzfugylmy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gthqapwmdh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtbppydjbx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtkdqbrtkp.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfmlvnkh.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtrzmeaxdm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtyagjpvmw.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtqkiddxoh.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvdfmktv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtpxsmvlmu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtzgoxdawe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyrevjdm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtncmvzwzu.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtfckllcir.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gttjukcqwj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtukjxiykh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtwpahhclm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gteuykhloh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtztwslmyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtsejiwwus.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtyvwwozch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtqfotjwaq.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtqmzumccy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtecbqrdhk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtvumffkwo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtjozwpzab.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtwsxgnvue.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gteczhjpgk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gttmiwjsrs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtyrcqsjos.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gthppahyoq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtmiwcuhqn.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtmirfcwsk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtsyrmawgm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtljvzarrf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtjjfzcxwv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtqynwrtih.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gtshsfeqrn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtrdwddmgv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtcypcygqo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuwmjkpbc.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtbxlyxmdx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtilzqahqf.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gttumnmnun.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtqvvlyynw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtaojczros.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtdcciprro.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gttoyxkqkh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtlqihxqmz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gthwkuzrfg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtiwwzbuoy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtcpgvxhsq.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtqckeukvt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtvypsbqnj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtcanteqay.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gthvttrrot.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtrzndxwns.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtdggmrnae.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtrjscvpfl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gteqbnghog.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtgufjsjby.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtzdegbrfa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtbpdvcbci.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtfdkwcpwc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtxpyxqnmq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtbryeffwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtdzpsxcpr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtcqdwmlap.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gttmrdmtxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtohniphpr.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtodvasugf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtcldslbuf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtsqhblzqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtjweqhpno.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtdrwuclkf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtunmgbgkj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhixingplan.top/Article/details/gtiiedkufs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtrjbrdyyo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalgictov.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtoqmzsxtm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gttmbchmjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtuyvlyuil.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtbsdbimrj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtyqphvraj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtoitckzks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfnsfarkv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gttofpaqib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtklnsggzi.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtwiglqlcp.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkckccam.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gttguznqhe.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtronlpwgt.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gttojgrukb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtewtjutod.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtrgzbkpqr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtqkcrnthn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtkhuizowc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtwzjjszgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtgzxpeguq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtrkjuikya.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtqelmyvuw.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtsoqttslt.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtahemlvog.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtqnkynbwm.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtxithuyxq.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtbiaiuegs.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtepwtukfm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtwozjbbxk.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtqoexigyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtudjhvecy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiizhcnyi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtatoeqvma.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtfzpwovjp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtwllcahbv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtfjnogeaz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnbfgfppk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtfgevzqee.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtegfadann.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtdtxhqjrz.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtreddsuuq.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtpvbixlqh.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtvqpturvm.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtusmkzjrx.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtiholedsr.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gteutbbouh.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtbpfwzlnr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtxakxtqlj.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtelglcyqj.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtytdlmxad.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtabzmguza.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtwilsybsm.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtxvxivfwi.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtnwcrljgt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwujkuhya.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtxenkitxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gttfjutpwk.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtzzrtxzii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtpzuqivlx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtgmsjpzaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtatvotbmi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtaxsfrqsj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtwwxhbqcs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtsftlchch.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gtiknnbsoe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtzssapolz.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtbygfyrcu.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtkdhiqyxq.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtlqsjavqq.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtmmbtzovn.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtofhdftjn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtvjcmzrcm.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gtlopuknai.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtxioinnkc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtljjqikxw.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtkqixznpq.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtsuahyeeh.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtsdrqczei.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtmrynhkdb.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtfusjmfzu.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzxavyzgw.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtohpwpbjj.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtyajwlqgt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipdzbpcc.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gtnfxqhuuw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gthimbgwyi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtdkahfnxa.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtqrrvylxh.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtxsupylmv.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtjhdszbbx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtubdyfzvy.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvkintsy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsekubamj.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtttdrdqkj.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtyoucdssv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtzzbohdcg.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjbckxwq.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtjdbtxcof.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtoymezbav.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gtiogdjkoh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtnaqkwbwm.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtsemejtqa.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtxgbdbcmh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtaknppoho.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtrhwlcqpb.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtzlejpbrf.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtkktodhmz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtsjdtlnyv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtqwsfkeds.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtrswfkbzl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtgqjyhgzm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtztdklopr.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtxpbpsvuw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyugnyibn.html


<!-- 参考信息 -->