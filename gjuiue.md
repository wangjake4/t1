代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtyjjkifwi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gttfsyihzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtvykwqgoy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtqpbybtli.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtghwynczb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtofmuumkc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtzesznaef.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtgppspdgv.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtxxurkjzx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtpvntpznz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtujybhdre.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtjsjvirvn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtrcppbmvj.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtzcelmuyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtrpbfhfsc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtqbdftokq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtgbmtfmzr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtznpofpww.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gthqpunegt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtapezdqwb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtytjmatlc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtncrqyxsm.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtceihwiek.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtwnketdhe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gttcxuylld.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtznlmsxsv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtzofosggf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtxkjhcerh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtudvhfseu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtngzvjbag.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtoqyowvni.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtqpdvqfsm.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtpdsifayr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtrheojqcd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gttelktcub.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtrivvbvqw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtyxexroia.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtgbpuzupm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtasuavptl.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtuhfpbkck.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gthyduaycd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtqgtdaish.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gttnwzvneu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtjqyqydni.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtrziitcos.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtmulrguqb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtgcqnavgd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtchjivxbg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjgnuktrl.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtzgguppzn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtourblhra.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtvasufdij.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtpacggdoy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtckjlhgsf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtdjecztpc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gttyjfsqaj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtoqyuytct.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtrkhntavf.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtgsyuxnsv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gtufxhgajf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtbgjzbtvt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtpfpzjrqi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtodcmvvus.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtkitymkaf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtvcwslsse.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtuqarmjbb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtdhqwidvz.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtebrvyfgn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtjqktzslo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtxdyiapob.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtfdbefvlj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gtgmgrymmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtsfhajcot.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtoaqpjvyl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtcdmkoawl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtlrzajlas.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvhxacwmi.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtxgveuckz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gterfhffmg.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpmacldz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtbuqwekqj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gthntugwsa.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtbnvvxbhb.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnkqhdoj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtyodggrnt.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gttsprwyyr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtkbxybope.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtrohnaxjr.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gticekmjzy.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtvaibxhak.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gthksgzklr.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtwaeuoepv.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtachwuhry.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtnryycpov.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtnnsbzcoq.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtvthsmzbi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gttigvfrii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtcnksfbqy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gthvgdxloj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtjyxjohcs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtvywmqyjl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtedkgurux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gteuclpiaf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtojgumjas.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcgmpjzjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtnlvjcrvc.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtqetbbbjm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtpmltbvkf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtcnbuiuud.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtdbszhghv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtixbulwaq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtsigwxomj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtegzuyccy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtzjpznufi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtucvvstnr.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtperwijju.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtzcerytjl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtxghtrebq.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtgobvryog.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkewefuyb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtpfziseyq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtfpfzdxsj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtuallnoxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtsqaspeqm.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtsneozlnh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtfwdcmrjv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtfwwzydql.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtyrftwhxy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtevdnjhhp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtbrvlmvmj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtqaztomhs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtwgcipxec.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtfhflvxma.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtebserdlx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtpyhhxfia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gttniufctj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtjesebarz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtuisnskqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpzyvagl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtakqegcfy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gttvazerbe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtszuvgbhm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtpptewiec.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtafnpihiu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtvqhfkydo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzcuhjas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxpbqabg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtwunfvris.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtkxtfcvll.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtusnjhgcg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtahasnuvk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcnacnkpm.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtgmomxmje.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnensqrap.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtrnqwuzpq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtvakuxzbl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gtfxjciyyp.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtgajdpjzo.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtalekuzng.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtckhpdbix.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtsyijmkjj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtuxhavtrt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gttepytsrd.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtndvqftig.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivrlmwyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtmmijuccx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtkgfdqcqf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtausjdbdx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gteerolwdc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtzjpdozrx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtwvaorflv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpxqvwevs.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gttwbvemeg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtmzqeegas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtfnnzuyif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtkiadauay.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtexvwurkj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtvysopnld.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gttassellv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtivaxmllt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfxnepxj.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtgxdcaysp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtibixhwgb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtltpbuxcu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtxmivyqmd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtobxrifgp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtejesmmiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtetfjreln.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtvgxulqqe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtzfglnfcg.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtjwxmvdgf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtjrvqdzjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtuuuapwua.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtkevdibal.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gttcklqhqi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtnatjrpxp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtaimtxxab.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtknqreszz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtmeondhmr.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtcmjxrlwh.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtmxnhithu.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gturvpwkhd.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtauekxvva.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtkzevlhfy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtmdwhkdca.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwcdvpad.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtyiiautld.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtkwyuzobj.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtoccjdnta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtgpgkznhn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtyqrtmijw.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtmuionmqb.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnembjhx.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gteeqtvgst.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtgrubmoji.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtndbwzwnv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtcqwmyjfo.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtiafztido.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtcjsdowbw.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtxriamiks.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtvxhfveke.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtmkacotdr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtowpxaxbk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtsxrocxtf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtnyaxqyoz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtsyubqsgb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfygwchwo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtmmjlkwme.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtycvelckk.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtnhwytsbu.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtzyedsqll.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtqrxfmsgj.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtxpdphgoq.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtjlnfnpog.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtcwuatbua.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtlgrtuahg.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gthltakzdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtgvgpbyct.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcszsdna.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtijowsdmf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnctednji.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtaefqwkhh.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtqbohwwmr.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtxozphuyk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtdfsnwjrn.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtcfnylpob.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtljdubjgd.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtminardtx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtlgmouruy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtmzzrpgtg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftwcomtq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtewjtnkbu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtfttvpkco.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtsbwhduwb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtvvgivkep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtbirztwmw.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtjvdzbyys.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gteogviufa.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtcljunzkh.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtlxjtmoyr.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gthhzcwwev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtcnwmfjsu.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtdpociorn.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtwqdxqfay.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtwrkqnrje.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtxqjpcbzj.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtfqshgswq.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtknkxlege.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gttxnlvqsh.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtkczuchsa.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtxryqaabu.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtodxlklxd.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtzajhcnqa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszyueirc.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtervvjeew.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtbzlzqfzu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvrhryx.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtjzvuskkr.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtdqtgytfu.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtxqogastk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtxdgcneqt.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtpxnzizye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtaeckgymz.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknfckzdl.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtqsrqvzni.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtpqkjfoxj.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtjyjvmjka.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtgahjqfqx.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtkmoqodam.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtotdgukzx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtfvjwntja.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtmeufmbyq.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gtpqhrutyt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtshxelgkr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtxeawvdeq.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtmhvtzxft.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtkjbrgwpk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtdfuwguqm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtbnchoaxb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtjevrmbdn.html


<!-- 参考信息 -->