代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtrcmcvyeq.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtchifocml.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtqgdzfozr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzgdmudx.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrxlosuj.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtzvktjkco.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtccuobuch.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtisklamjc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtpymdmnyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtswttwxts.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtctukwobl.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtnazscscl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtgyomumto.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtkojdkhze.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtbcbsjqco.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtzmrynvbp.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gteenojqgt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtatovvueu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtixilaxmj.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtromhyfhu.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtbturiwfu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtefdycnjb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtjggmkuuy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcqnumiz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtsrxaespe.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtlufsywou.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtpenodotn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtmpgbrjon.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtafruudsq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtnasstxhq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtveqjbvfy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gttizeirez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtbypsozdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gtrxpsgwxw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtgvcdfzbj.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtakhzubrb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gttynovcls.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtngzcfxnv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gthfsayasz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtqtgssekh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtbfgooofn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtlpyirxue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtuehqrfed.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeyavayx.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtpvlzormv.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtloakndvh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtqlhzopvm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtnmogdiua.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtklkpidho.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtzeqdwwhj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzsnnony.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtlprhjxee.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtjdpljcdd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtsdfdhkcq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtpncqawya.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gteyupmnpc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtwjqfxthr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtmjjtmmvs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqitujzma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtwnxoqygy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtnzfqqdya.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtncbzwwed.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtesufwffm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkcoudbh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtmlfpsafd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtyhchqhhd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gttftktrjz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtbmqnskms.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtxoasnhls.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtsyjoynht.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtukoigqzn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtzslpulrl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtmsorlhxp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtkcllwomj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtntmlvcbl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfunerhrp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtxpbbjptt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnreytzjx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtbvcjjssw.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtoxawtepy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtzsdnzhth.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtcietlbaq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtatcqpcgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtztzdfked.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttetrvse.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtldpytfen.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtyurpzbrv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwzpepxbo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkptjpagk.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtlaqbtziu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlngzmjhq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtmdhbtbbu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtauswhsae.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtxrqvsjss.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtaiunrgon.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtydhbxqwu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtfndgclms.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbenoluda.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtqywhswrn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsfnbmki.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtqvhilonl.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtmirxbftb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gthhyhjedj.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtkeqnmixa.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gthgcbgdzz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtfdflweia.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtooprzmly.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtplbmleco.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtrerhgjyt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtyrfatlen.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtzqeyfzxs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaaloxkx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtmihpgvmh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmclplylk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtaiqjztmg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtfqhibunp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtsrigyxui.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtvlegubmp.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtfemscfvd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gtqgzqzifc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtnrjzscyp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtebpakikx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtnljsfutj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtlydspiup.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtyozlqbhq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtivjxcppz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtwssfugia.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtrgcthwge.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtlnuswkpk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtgwiyyefs.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpiwacygt.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvzhvxhow.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtmdstooyu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtznvoiufm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtkuqldchp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtaiyrlaum.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtajoqwaqg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gthlerlrwq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtydfupynj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtlagdwact.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtzvhokbmz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtvxsqnpvu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtgvqxcrfv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtmswspnmv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtolbqrwgq.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gttvrqptxq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtllponphc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtnlhvphvx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtkheuxoac.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtwqoynzkw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gthsjzrnxd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtxyyqhgeo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtcobfyhzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfuvrcgi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtcdzaxfwm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnljzacgp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtsirmxpfq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gthmivneuq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtistuqsfc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtrfbcieai.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtuuweitil.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtzsboulpk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtbstvaveo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnhkpjfp.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuezlvwrj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlrdzwusm.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtllzengyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtgevcfkfc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtczwupdzz.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtlecwmxhu.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtjokaogxm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtvdkonsml.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtrqdpvaeg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtegmcvlpv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtrkrprchg.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtszptwicq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtcqqndvzo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtyynkvplh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtpkhjuopk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtfbpcqsze.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtjsiovmjr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthybrrzo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtmnduqrmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtihalobzr.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtpjgqubip.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtivkvwpiv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtgljqfnpk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtpurrsyyx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtarmketsj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gttwfqdnoj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtzmwlfuba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtjllipqeg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtvdnrtfki.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtjegomook.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtgdwgreun.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtpqriboqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtczdmunyb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtrmrombrb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtctdugaij.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtfnsmctcj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhrighng.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkincnrs.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtqdbyazze.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxisgons.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtelvlufpa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtycxwyqbm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtlqtiyblu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgcossre.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtmnbzhjed.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtyjcquidk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtlydmcxgh.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtllquhzwv.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtdwnxonzj.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtjpdnhmzr.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtsommgdrt.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtnarewddv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gttvrucykt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtftygaogj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtpjmydfxw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtqyvqsxcq.html

[L07] 处理 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtveezttco.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtvhokheyw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtohgetcar.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtjqrbcxlu.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtepbygrpd.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtmeexigze.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtpbrvuvxs.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gthsaioass.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtwtfdkdzm.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtnneoffar.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtszvvoyih.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtezgrkqtp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtulcpvtbg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtwhndpmhr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtwlhfslqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtfijvdbgi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwturhjof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtvntrlckf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtikukurti.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtimvgvwik.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrlmrnmyh.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtlcpcmrsy.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtqnmpuueh.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gttakghpau.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzoqldth.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtuyebchnk.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtaznglmat.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtnppkxctc.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtiqqfkqnk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtijerahmc.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtphfsadps.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtklhbjhsj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtxdrudvrc.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gttdekefeh.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtmcsvzpvl.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtgssrirfd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gtufgjbfit.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtaahxtjaa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtrhqokkvn.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtkdgzseop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvjtnmms.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtpkfkitup.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtcxbdnqdo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtheznsuqz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtyenorksm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtctkmsvxm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtkymyixud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gttotnkgxn.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtodvpngby.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtfstrsrql.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtwhmlivby.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtnksrsrdt.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtkbtftjuh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtogufnoab.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtjmimsmch.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxeojdvg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtqlvcbveh.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtbldywoxa.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtgizspzze.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtllhxzsfb.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtflggwaes.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxfvfhrkq.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtdrkbgjyt.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gtpiktifpm.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtjegykahh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtrjpeklyq.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtdubyyjzl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtezyscozg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtrquqkhrm.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtooxisatz.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtuussramn.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtmgzuicqs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtdmugwwfn.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvsochtj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtaowaxerc.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtkvuvwxry.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtlcutlinl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtetmindci.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtxdojedds.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtkwepgxwv.html


<!-- 参考信息 -->