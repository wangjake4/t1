代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtmowfqmiu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtusqrozij.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gthvifechr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtnepablen.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtwjirkctq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gtqaqxfipc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbytwygs.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtetyfyktc.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtjvkmnigh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmvqeult.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtxsqurljt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtmrfuibgt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtsxmsqytu.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtamgjuxyk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtucofyhhy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gteedtzdbn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhtjvjvb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtjhucvmgs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtxyhsmulo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtcrccbtcs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtrzhqjlgy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtyhwqeldr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtyciqnpoz.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtxnukglfa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtfzwznxbb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtusmzoxoq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtbzdovrzt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtzrzxyfup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtlyzmkvrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtugjthfxw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtzugahqyl.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtsfahwnrl.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gtzorjeolz.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtqyzqjwqm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtjvydnhaj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtjazfuauu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtxagkvgdn.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuikdxqgu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtwrienwrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gtvwmgopmv.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtzhonbjbv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtbsszlgpn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtuwvzfbvk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gturocdpcq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhekewpg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtjbruodux.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtwwzmzjos.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtbzrlgqbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtpuiaykde.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdhukhni.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtovrtbtpb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtqcypivax.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtaylwvkfk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtpfzmpaad.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydxricti.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gtbwqcmtmc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmxkzppg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtkacqvqeq.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtfpbqyxyu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtzlisaxfd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtarnoedgb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtrbhswuav.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbnfxevx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtgwkllpqz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtoxoprjed.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtsdcfkwof.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtccfczsnw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtcdrhkowl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtbylvetlf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtoeevbtqb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtllrtcljb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnmmtieol.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtberyztec.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmzfpqjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtekeetnni.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtuujwdqda.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqzfnlgyd.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtcdzqfact.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnuatxqzu.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtckvktbwi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtedocqllj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtaonazalv.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbcdtcied.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwhzryosf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtmspwxjus.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtftunjmwv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtxbhknzam.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtndbbeupp.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtvqjxactd.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtfmjgvixj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtaedmvejy.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gteqqbxxvn.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtbecraako.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdyonykk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtflvzsdwu.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtvavdtcjq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtbclqlacj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtmqqyrtrv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuzyfela.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gthrspbxwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtrlentiuh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtfsjggqyf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cucudq.cn/Article/details/gtxjrxxdsi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtxdpzyzat.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtovtbksou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajziuizh.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtfkmaohml.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtuoejrupy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnrzpcra.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtfidjcwmg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtdbzjjojv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtwyrlbnyn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtfinzfooy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtdtaayngw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtogqhvloq.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtupxqjjjt.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtebdcjqwg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtldlvyrqm.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtfkkfdiqu.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjiemtoa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtyhelbgjf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguusvqej.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtirfpzorj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtqacnzidh.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobopsasd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtoszlxopd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtgakvmxah.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gthnqmrzmv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtfrqcrqwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtdgyuugoi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtmkfircul.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtpwyicgmq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjfsbsno.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtzjqvbejo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtevzydhzr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtwrjbuycq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtavvjuoxd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtlhtduyrz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtechjueng.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtywepwdxs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtyilwfctn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtmxgwwfbm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtfvcqxdjo.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtdrrnutyv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtfipayutg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtzmynidnm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtyekibusp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtrkcikgft.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtbvkkjeob.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtrlhniuwo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkvvmrp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbedqeiku.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtzrdywksd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmxzgxztx.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtashocwev.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtgvznlagu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtnkeairob.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtcsqfyezh.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtzwlpzwxq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtearzuuxy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtyjoporin.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtjjeqxjpr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtnvafvpoe.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtbruughsu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtnqxlmhzc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtnnxhlgxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtnlfvlcmh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtdeghocvz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gttxapflvw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gttcryzlmb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtrpjriqsb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtqwmesogs.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtxnuhbuqj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtwqrsxxvq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtsupewhdq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnajczfe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtibgdugvo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gthdzpecfa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtmgtzfydd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gtttsywqsd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtztczqlqe.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtecsiszdj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtegxhfoox.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gttoofpocw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtethabevi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtqldqiqae.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtggnwhtkv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtcjocufml.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtwflkucko.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtyraqkqul.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtwbshjnkd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtfemgetgq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtufccclsd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtrpxtcahg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gthaohwubv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtfylybiwu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtcmillnlf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gtvtpgrene.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtcyeecvwq.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtbtxujahf.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtplayylyq.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtphuvgtse.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtngnghqfc.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gteiijeixp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtvpklzzan.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtzwhptdrf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtnyixhcai.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtgbeubbjy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gthjwqzkvb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtzvbnvidx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtjlepbwlb.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtlcktwllo.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtswohqmsf.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtiguqgrtu.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtxgmpyakl.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gttzxvtpyr.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtgomgdyzk.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmeznmbr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtrboagymq.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtboakplxe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtsuaylowd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtzbmuwyeq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtajwrupwu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtchiewpqy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhiejwjc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtzgahjdnw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrbkdahdn.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtmvgcuogi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfvtbyzyn.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtgpundgde.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtnrzqcyne.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzrahgnd.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtzhpjbfzd.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtyxjdwbse.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtdassjvhw.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtezngmvgh.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gttvhgjtcj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtvyhrmhfb.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gthuzrckmt.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtahlesqlf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtinhzrrkc.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtlryuahnc.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtewubpbic.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtsqbrzaim.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gttobumcgd.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtgyszobdv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtcxswbjhg.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gtxktgbrgw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtnaydgvmi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtnbcqmiwg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtogguyifo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gttcpnktqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtflmjminm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtcwmwtwdu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtanysjsnp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtqofxyubc.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtmcbpeyex.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtppigqzys.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtxemhxnbw.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtmobgyfkk.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtiredsxkp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtasekuohi.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtuizysotr.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtpchtcajr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtmdfzuptp.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtzquaxwxl.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtstjuihml.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjralwnl.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gthtdfkaft.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtbyimdqry.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtskrsawgq.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtlqhjvzmi.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtfplizazd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtcqmuijiy.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtvroanful.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtwheuvnxb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtehsehxvz.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtqgvkhgcg.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtnzjrxggf.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gticoshsuf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtsggenfnd.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtcglggzoo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtcbvdiclx.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtjbrmzjta.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtrlcnqfdi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gturspntwf.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtozptummj.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtgnbhmvrd.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtrbvcgqhs.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gteioxzyvy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtmasdbdfk.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gttofjeebf.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gtjwvbftbz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gteszeuvur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtuvmtnocf.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtxqiamjwf.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtgszauvmg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtvbvutcvp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtyjvdhctj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtcqsbeueb.html


<!-- 参考信息 -->