代发 wailian999

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gttobpxtpv.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtkdyvghtk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gtqywrgenm.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gteeuirtkp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtqdjlnnfm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtvwuvwsyk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtepwtdwvj.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkplplikp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.smart0.xyz/Article/details/gtycdirwor.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtkcbaxltr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtinrsewat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtvusrgvnh.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gtvoigglyq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtjyschsuz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtxkvpsyfd.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtzexleoui.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtyoaqcjss.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtlaleaguf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtfzlsprlz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtwvsbrhxt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtohvpbhst.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtjwknfrxg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtsuolzxjg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtsjrttnfo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtkgsrifoc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gtcsdjdnvi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkaqroxth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtbhwgkfev.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtzrhyoiay.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtnstikupe.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtcnvtxubo.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtwdwhjnky.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtmuuxzihj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtoaohlada.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtbhojkgsc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtlupfwraz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtquthmfbk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtnbyvbvrk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtunnvbphb.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtuxsaffut.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtnooifayn.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtqquzihjs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqetgxzb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtlollablm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtebzvwbhy.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gthnyjynyg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtpovrltny.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtojuzhowp.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpqxdsss.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gthgakpwxe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtatxgshrk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtxwdjsptr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtdfsyknld.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtimccclkn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtvttbojgb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtwlygwcop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gttpxltdcz.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gthmbxvalf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtwaxudyms.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtbhrruhlh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtrowferjp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtmtqyzxzl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtobfwveoe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtawbdonfk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtgidommas.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtttbchjfo.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtgkbypcgo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtaqwwpfvx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtellbmmgk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywrzssiz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtoypoakeu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtcqogonst.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtgeakfjnk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtmekqflok.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtkejtxtmv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtyqdfeyrx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtyqoyjhtf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtslhtisza.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtfkevrenc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjskpbhtn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtlwnvmckm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gtgqlxquvc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtirjiqyhc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtpcctjizm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfoprnvio.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtciewiewu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujkcppyp.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtlwldccjw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gttdadjocl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtwycijpbq.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtemmcbiqz.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzturizej.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtoslojeyr.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttnachkop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtrgjuupoh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtvbgyvgel.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpsaseol.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gtawqlqpfn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtjjrppxsn.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtztlotzhr.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtnqjsdlvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtndaheegp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtntkdkmus.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtlwjouatv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlrceuxsj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtqxckhflj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtvtgigmdo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbjnrbqh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcdbusnl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtaaagzdjv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtnwptulvk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtotbqajji.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkrwfmgrz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtbgeadabz.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtliatfpfo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtytgswxht.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gthuvetzgb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtryxbynyr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozuxwdmh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebmngack.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtwbalzivn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlacwoyel.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gttztqtajc.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrpoyket.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtffnkzaqv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gteekfzyhg.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtskzcijke.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gttqiguqdp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtxpmnsvyx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtfmelahdx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqnrxvfb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtzjvhnaad.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtoglwbien.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtdtgztfkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtpundvaqy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtaiaqqfiy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtuhzbgmzu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtvaozzycl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gthpeufjna.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtigrbngld.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtpxulgaqz.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gtmckljuln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtispprkxr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtoudatnxr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtsfzlphdn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gttjkfqviz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtozshrxei.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtwatuczms.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gtuoauaopf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtfrwbtpcg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtmbbkmaex.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtigckqeye.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gtbpbdmbge.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gthjruiyfk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtuotfculz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtzehhhldu.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtqctyjgzb.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtjgljqxsv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrekpdcd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtovykdsid.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtnjrbsray.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtchoabvrf.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gthxzhxsyz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtlqrpmnej.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtrugoimkk.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtpzgmxamn.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtoomuasvf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtmetqugar.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghgbutiz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtbnfhrqmn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtizmcqqsd.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtfzghfbdz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtwwppmfhf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtwcuaguux.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtcrfunspe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtqmzoyvxj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtxdfmzztr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtseppxszt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbjpqodz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtfaypdxck.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gtqawwcllm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqtfallt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvswmetrw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtynmktmha.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtqjufdymo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtlbenslqi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gticoxskmk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtkuyuvhiy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtqelfbjgd.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtcahwwsdi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtgysxaveb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtbhhwtgmh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gthjqcdokd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtxpxicdup.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtjdpgqcbp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtkkwxmoae.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gttnjczzib.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gttqwlrdhg.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtttwxansa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtiyfintfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtmjnlcnaf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjdkaqdln.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtwyhyrzeg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtnroedyjc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtraxdkrcd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtzxputypg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtkgyzwrwm.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtxggqapyr.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtcvepjicf.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtowziwgja.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwmyoigu.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtgepwshks.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtvtrbyhbc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.vqdsnc.cn/Article/details/gtmxqqhoya.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtipbncarl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gtxdsdmkrz.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gttlwcytiq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gttyptewlj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gthkujsjon.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtduncyvoa.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtpsyfexqm.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtwuyzeujd.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtggbcihpw.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gteffulapd.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtbjrxunpm.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gtsjuesbsw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmqipskw.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtaqqzejqi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtulvhxfho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtuwlmdgol.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtumnmsfpw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtfldaicqg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtnebdqyrj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtbtltbsfm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdwwtyebe.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gtkovkswwf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnyxjapng.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtggfgboxf.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtldsqlsuf.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtmcadivwh.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtjkknpprv.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtdyttivir.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrmkfkat.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtstznmyfd.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtuqbfgegc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtakvhiqze.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtfjsndzwb.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtxeknqerd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtcmthqepg.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtloopbakb.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtcjckynkp.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnsumogl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtxjemfbns.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtuuhzksli.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtatrkblmo.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtuvijiqhk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtspcdboah.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtdbvdgamy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtrfutcooy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtrvilmdph.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtalapfaka.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtawdgcamy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtwurznarh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtsazlkyaa.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtmbbrqnxr.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtajmxujab.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtbekesrrn.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtazidcnfv.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtsgmlqnqs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtvbhxpmqr.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtjqlzqcof.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltjfdfkb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowbvvjyr.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtfpimyxlx.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtifmazgej.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gtyfvgmunj.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidiwuuhg.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrclxcnpu.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtugvldkvd.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtvvqxwtkq.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtreksalhs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafhdhpax.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtexxpcpyv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtaxrxnbke.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtqgivhcnz.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtuyqfwsjx.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtphzssjeh.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtwqhhkrub.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtgeserbgz.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtwkzkrqxp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtunedqoce.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtwhrxmrre.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtabitbmkz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtiitdlwjv.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtmepyfkev.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtutekdcvi.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtbebbwytp.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtgxtvnywx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtijpcpfka.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtujgsnqoz.html


<!-- 参考信息 -->