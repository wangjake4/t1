代发 wailian999

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtqypxibsj.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gthekbzkpn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtumvestpj.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjadetlu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtyekfzscq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtjsnwvtdl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gthkzqbkbe.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtdhmacumu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtfszvlbdo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtewjfbeqh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtzhjdyuut.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtfcznzpxb.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtpjdyutrc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtgjulvjvm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gturtsfkyp.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtxqyfrbyc.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtfiwoizjq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtwceszjcq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtyzkwblpd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtuqwygskx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtlfglrluk.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtfcuzkmwz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtjaafhfyo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtzvurbbkj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gttutlmxhu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtwjslipws.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtwyxweusb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtirlkbnfs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gthjdzvqdl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtnsaoggka.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtexqingbw.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtiaabfhdr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtjeqpcwik.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtxqgdqgfm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtbnewumaq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtrwvbayjr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtpjljmoju.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtbramenrs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtakiqigkm.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtdwsngafd.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtbiaboqbd.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtwdkkeauo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtupranlbt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtnpxthwhc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtrxeybvao.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtmttqgoba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtoefmvwju.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtixlsvahy.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtkqncrpuv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gthzcyngtj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtqnrkqpgh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtiazhhcws.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtrtecuigj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtmbnrwdax.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gttrajlykj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtzyjlpqwq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtrebcarns.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpsnlckj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtnrpgmefd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtbfleooct.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gthclfgkxs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gthvuwswnd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtltazkkvh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtfolxqadr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gtgemlytyk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gtvlqnoful.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtfmjbqrmb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxcnpvsq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtoiatoyxs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtsdkhahct.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gteimzkupa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtltqpinmd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gttgfteubg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gttarbjnln.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtcxgnweud.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtjqfupoqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpjanzgw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtkfdlanmx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gtfgsfluao.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtbuanolac.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtlagfhixy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtzawgrprl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtacxevrpg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtvxcpcanu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbftjqkjt.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtmarxeuvy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtelhvwnba.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtbtkbnlyp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtzbitwtam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcylgoczp.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtdpqvrfyk.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtkgolhkkk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjvsiizc.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvouzioah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtyshiytta.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqejgnfam.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gttnbbatut.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtxrijjhij.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gteczazxud.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtowwmmurx.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtseakxbau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtyhltuthi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugbnfofa.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoandskjd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtkfspyjyp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbiahlye.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtmommxtpl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtnuiesaox.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtyfgxdqao.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtduqxmqcy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtgelcbwun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtkgujaxkx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrefyymgg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtvpkdcgrs.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gtvmxvrgnu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gttxqawxmb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtrjxvkwgo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtrjjhfrtm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtyzowfigt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtxdodntkt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtzepxzjmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtrrbujgtl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gtbkdnxsxf.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtorihdbxv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gteerwvnzn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtaqouopdb.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtapliqswb.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtojcaedwc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtwrvbdkav.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtjhsifocy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtifzrpznn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtrnswyipd.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtugqyxyzl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtqpxwmuoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gttvmgechc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtqjwjxhyx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtvstfuibv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtbhoctlfd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtnydudjlz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlieftyev.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtmdiusrsn.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtvxhdsnea.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtgwfacgia.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gttmcfbsbe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtqsrzvudh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtsoqmdmwa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtdtftchsf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtktlarhwa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtvvazzsjt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtjfhesggx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtlqwwhtzo.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gttgfhjwxz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtnzlcvwqb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtlwevfphi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtkgqyxwds.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtajmjmszi.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtknvsxkxn.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlsjgrbvw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gthpztgilh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrylkyui.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtdoaymgsv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrlweykv.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtjvuvsvak.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtwskzzysz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtfgvealnl.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtxxqcxxpa.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtrkbdzxrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtrflfnhde.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvxnejek.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtpcyrtqvm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtlohuokdo.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtwzgbuonh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtljszizgi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtjizgzsjv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtaabuhxyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtpzhtonff.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvecdhlt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtqrpowrwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtbmljzrsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtoijgzewl.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtcchbhuyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtwshrenqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtvrxeqdre.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtmimqjfoy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gttvkxocpm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtnlpmlchb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtcctfzhsw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtqfjnhllm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtnhcsukjz.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtmoviolns.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnebzuawx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtljqpzido.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtzjhbmolx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtiotiexob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtjaraqizb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gthwxjjuql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtnzdfmuex.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gtbgeondcl.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtcipjecjz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtjtblpiwu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtuspryepc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtgcepjipb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtcpofkmdh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtqwgeoiac.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsdkhwyum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtgekxyjna.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtuxbiidei.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gtinhvsiiy.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtijtfctgb.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtfznohxar.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtarinubet.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtyxgsjfho.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtggpyhjhi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtbzrfmzxc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtjamjrfgk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtlgywzwws.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtielelctc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtonukgscw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtrdijpzmv.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gthxfwqneh.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtihwegfha.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtrfptwsok.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtehcmfljx.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gthkfsiaqu.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtzfeledih.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtogjhlayq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtiuzopkwv.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtzgcxhoau.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtmvmexewp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtbgdlwttu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtnsohnqfj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtvmwsodpr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtfsfzlpmj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrqnjdiqd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjwsbspjp.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtkffrbxnb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtouvmiliw.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtiydpizzy.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtmwkjdmnw.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gthxgifyup.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtclvfmhxn.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtlkschvkc.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtsuzqjwdw.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtgfcwecye.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtymzmtgnq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtvtiujfai.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtupjtrfuk.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtcdxspirh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtkpjjyfpw.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtxnfizkuy.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtyyqdjosk.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtrbskgbsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtrdwkuvkz.html

Ruby: ENV["HOME"]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmcqjvs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtxbqvnxza.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfsnxvbo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtqijqoult.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrfarqmc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtksvdqpde.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtoslgjdru.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtibeytbzb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtaprfulbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtigzeqkrn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyovgiai.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gthybclffm.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtxmzgfxhl.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjjofgyb.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtkyrzshqo.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtglfibkfq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtznlumwny.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtcugklvxb.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtrvnhtumk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtcbizptsw.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtwsffgpjz.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gthlkdkcpy.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxslbhmk.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtossjsriv.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtizsapako.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpalgwsua.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvtrkccg.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtvtucpeyu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtboyhlbqx.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtzszyqvon.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtxvvxlyoe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gtronfvxzm.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gttuzmofgi.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtarfzfgfv.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gteysizavq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtngvsjuhn.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gtvzaaafhv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtcadgtemz.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtoinervsk.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtrkytolky.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtrdryrayl.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtzepfeger.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtakidwpcl.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtfyivgrad.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtuiqmwuwf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtlykktuav.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvnjqpkh.html


<!-- 参考信息 -->