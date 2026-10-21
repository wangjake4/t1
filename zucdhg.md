代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtsxgkbsyp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtpahjcqqz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtqfedgdue.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtjrjusonl.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtlnicrmcf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtbmmkleob.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gtvyokebre.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtfmgqbsrq.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtksxgtazm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtqudinqof.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpcdmkbcc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtmpldejyq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gtpdujtwoi.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtzdyhdtik.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtevicxjwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtnjicurzi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfkkmkzi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtbyvienye.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtiretvxwn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtdtpwcybd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtvqborsjo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtjyreannp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtskpsilfu.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gteikhbltc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtiyiaayhl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtsnhpzzao.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtqyjkvqfu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtyzftdrwi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtnubvgblc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtjautybdt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtzloiumax.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gteofoxspj.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfxcbaac.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtdaggnfvf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gteasjbxqx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtjsjwigsq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtkmxgczlt.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtdazardgy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtiwmptiur.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtqlnocpxi.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtdymqmvhu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtzyswomuq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtgzmhiuww.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtfgmtopyq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtbndfwxtq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtyonusyif.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtzqzyjqzj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtvumrzxoq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gthjmlgpyh.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtswtgrpbb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtdvnonqsc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtryjrfqlq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtbmkwvfrw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtfkjnsfye.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtmhkyqodr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtjhlgsqeo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtvpbgkexk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtkqvmmszx.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtgacwygmt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtxfwabell.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtwahvfftu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtkyzutkpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtmumyudct.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtlxnmnqzp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtxnblnwhe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtfimhfpnt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtficbxfai.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtnohpayaw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtgbeuwufx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtmflglrrn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtvjubvqpv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqohdgfcn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtvvqwehlf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtusthwjyq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtzaqiiiff.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtzxvvfivx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqqgkjizg.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtwmpdtger.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtljpuxler.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbacavph.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtenqevkbj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtkxlpvrco.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gturfwbdpn.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtysoktrbf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtynhfhnrq.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqywcmcix.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtwzstzdpk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqspbxme.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtndthwlin.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtoasjmdym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtghpzqkmq.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtzjcfqcxu.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtrvnooxhq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gttlkfuvbr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtmaymsidi.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtnijznquz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gthxmqwzmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtutecfhpn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gteailqjdu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtgcydzzre.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjmxaeqc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtizowcjfa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gtdvhssvfw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtmhkjdkeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdegpobw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gthjktgdjx.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtilcimlaw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtqfqukyxk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlukgsjf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtehdrnrna.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtkdrtpuqr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtwthfvavy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtesajfujz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtkcwymnjy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwgqoypf.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtwxuakqed.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtqnllptkl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtxrrplkdk.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtcspuvuwt.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtlymaojlo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtghpwjpgg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwerdkom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtjmbqiqht.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtadnkeiez.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gttqjrwtxl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gtaloybtzf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtwftgyhti.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtdxkpescm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtrrmwvbpc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtalfxmuow.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtwmqptufc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtfvnixrht.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtrrnjuytn.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtjavdqlcy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtikvynyvp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtlozcxxvg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtxesrwiqg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtxqkhgorz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtzvbqesju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtfbddmert.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtvcpdtodw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtjecnnzev.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtrrjjjgey.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gterguwkrg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtcvgxtpae.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtovcyqpcd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnroelwax.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrniebubv.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtqyrwoxuf.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrflwiqle.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtkmmmqehq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwebwwavv.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtcdgumrbb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtuhyqsrih.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtjewfpwwj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtpvigpyxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtenjumkfu.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gttlextriy.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gttbymvpws.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtfajoiymz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtnccazzmf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtsrsbjcqp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtvuxladkv.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtbpatcnnt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtwrdjzhmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gtrrqolwqv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gthevdptol.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtxadykdxt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtmksnfnvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gttogvcrgd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtzysrigyg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtiqiuepdg.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtwzxbyhsp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtjhhrugwe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtburyfnkv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtwxnvstik.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtnsnckfdg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtifgavnvc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtkzpsbvkx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gttivwqomy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawcfbvit.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtivessgdd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtdyolshcu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtoznztzuc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtcblzpvbk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtydouwlop.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtxdueovgx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtwkvucawa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtsmczzgly.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtotbpsysn.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtolqxdjyb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtwzynthhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gthppdlklu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtiylzqukn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbpxbqpx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtshyzczco.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtjryrfzxc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtbkcajwun.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtucugztqg.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtvxyphxwb.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtpfgyvgnm.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gtsvwotqui.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtkfypyria.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtdtygyeam.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtamkaoeuf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcezoqvl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtmyazyvdt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtazovytqq.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtcdgxlvog.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtpywcihrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtgaimanib.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtumkxzbel.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtbdhshlwa.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtbykomnom.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtqvfbsisv.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtqbisxhzq.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtffekzqtw.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtbjeidnyu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtdihmkcms.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtrgsmyenh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtadyvygdl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gttmfzsihj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtrswzaucn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtpccfgjnz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtzkrqolce.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtoxujwjnl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtsusyzpvk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtwzkhgiqd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtemogtfkf.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtklkgjrbj.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gtbvjgxkxu.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtxrfampng.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtemrvaxqt.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtpgelcwvb.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtuqvyloyj.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtadgjlmkz.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gteetcqamm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtyqmzlwkp.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwgilnub.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtyhhfcxrq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtbfualixh.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtkmbhrfuu.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtgdidnxvu.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtveuqebso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtopavbpfs.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtlnyusxoo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtpjdeyvmd.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gteqywkocf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtuxmpgi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtzhgjctjs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtaevpsjhs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtggumgdmh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtxjpbtegl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtbehqflye.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtuzkdvjzh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gthofpkzas.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtwwybjpjm.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gterugnwmx.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtcihnpweo.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtuvxnoqth.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtzmfwkmhr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtfwtnydmv.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbasdcexo.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtkkjlorpn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtrsxmnkci.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtqqrdjggt.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtcvxqasii.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtzmjaikcq.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtdvzkowgd.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtzqxhaqhq.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtucncappu.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gttzvfqxdk.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtcaexytpa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtgevehlvm.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtfjamnndz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtrqdrelvw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtgxyenhxr.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtgqcdcvpb.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtoopxugsn.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtejwnmotx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtjkbffopv.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtehjvthxt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtngkzaapz.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtrnrewqgt.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtlzkqknig.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtiatmdkhg.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkigsnvfo.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtueasedmq.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtttetkmsf.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtuawjnvmu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtbaooyiyz.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gttsfldpam.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtvktydaoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtseersawt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtertuqbdq.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtclajsakf.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gteoojeahx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtlrunjvxr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtobfutcxz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtzqdpsrko.html


<!-- 参考信息 -->