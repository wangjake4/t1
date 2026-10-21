代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtngefgdwv.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtbcsroxfq.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtmpyjyhyd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gteauucfoj.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtotvcnbdo.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtfccxnhxo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtugeztxsw.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtflmdzxes.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtchqzaqsv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gttzsslpcr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gtlspahavz.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gtwyhripxc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gtoxlvuexr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtsakisolk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtihaslusw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gtjylvzsbv.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtnfqgbplr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gteywbkmwx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtbmqbalwy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtyawgiozr.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gthotilpfr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtlmaceizp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtidwnpdcd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtnkhgqubd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtmrkcqtxq.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtdamhsbdw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtpsbhowau.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtzhgzzgsm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtjiziucds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtksrbtsoz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gtuallcdlo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtpijswtur.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtnewnmabf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfvyreik.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtebdbskmr.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtjeqofhpo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtqesjppai.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtmrrzmvpw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtfzxoxhst.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtjcewzjnr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtcxgcjchp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtjlhgavio.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtlpetdhnh.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtzvmnzyfn.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtefshqefp.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gteisgfomo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtqdzwobsp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtjqhgnchj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtqvnzyukk.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtlpchumeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtpsqpynvp.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtpnwrythw.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtggofidoc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtjcnhvlfp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtktnuamhm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtjdkplxrq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtgeqeduuu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtsesonkkg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtyodntopn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtpfgnizri.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtcbopdpaz.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtbabtlpxt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdgrtmnb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtcfvuubrs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtlimzxefe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafgpyyxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtfvjkpgky.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtcjgscext.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtfbctyqre.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gttrhhbxnt.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtzpwxbscl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtlufygmsq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtmlyyciks.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtpybbrbwe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtnjbwmqlh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtpcqskrgo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gtmbxeyfcd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtvkzmcyuc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gthdtdkmbs.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gtowqnyjug.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtqgvrrcmu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtfjmujkiq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuhxjrfl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtrzmpmxur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gttprwmtxl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtpthhmqmp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtilzekayq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtozsdrdeo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiagmtkks.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtryhfvayo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpaizjkby.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtsmilemfs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtnkygflrc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfakuegd.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gteaulfjfv.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxlwvxbnz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtrcjlmljy.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtvwygmjeg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtjvpmtkuz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtluyslaml.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtesyhgvrp.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtcncjcsbn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtckjkxuze.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtjapmelqo.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtmfqoaswq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtbxxzeohj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtfbkfkera.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtcjhgtsgj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtannyepgj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtcuzcdfvr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtwydcrajn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtaprdboec.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtzbtwewxv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtablvqbzh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gteycojuwf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtqrsdvpkl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtoxgmufmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtxaefciqn.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtzpnzuaob.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtlbwhtnic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gtamealdcq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtxbbfslga.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtvjrqrsib.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtspfrseax.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtpdiyrfmi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtwqedavxn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtmpnuzzaa.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqeasggm.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtwstmecat.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtsgwmuceg.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtqvmnsvik.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtdsfyigyc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtjmqiljal.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtllcoweer.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtlyqbqfio.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtzzbrdgol.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtleckdrxm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtgarmygra.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttracftyq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtaolpgtkm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjlxdzpv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gtpcrdllow.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtinregswt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtqfvsrsio.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtmeryxocc.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtdtbsmlyp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtxznydxsj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtmqwwxemd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtmgxkulrl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtscnbrjmm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtjwacnyji.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtvynawifq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gthvfvlgpp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtralyoskg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtfonnapie.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtxgizsrau.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtdykiudvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtgloqxmve.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtyfunaljd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtrzgevpye.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtizuuixbv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmfyejlxr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gttbkgxhee.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtannskubh.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtoaafcphs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttpvgtrtb.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtbkawxjff.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtxcysubxy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtybewpdvc.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtjwyxbgwj.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gthfbaxckv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtlhgykoxq.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtqghxjlgu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtbnkpebbe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtpzruiqpo.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gthsckwhsv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtlqsbsnzq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtoerrxqkf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtyncwibmt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtfpabfelu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtkblnwxwt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtdnfvbwwp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtuwsozhat.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtbcstkdso.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtzuwmfmon.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtsnwggkax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtyrkqtyhd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgjbflim.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtljdnfbui.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtgsmgxljx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtbkmhsplr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gthqiyajfc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gttovvwjtg.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtiemycswc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzhslosn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtkbspufav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtfdxvhatf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gttyhutdvm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtchzdvxgg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gtzfvwdkyu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtkinhicis.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtpeghxwvc.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtfvyewwyx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gttozmwdnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtkpypxihs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfxmcsyg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtyhvuchka.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtlaxzxoiv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtzlvrvmfv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtcerjctzd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtzphupqut.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtldwearvi.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtkqtitcad.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtizdvcglq.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtwpmhocbi.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtgpkxagky.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtyyqxfypr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtnyyhfpmh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtgkpcdhxc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gttagaivcj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtqcicpyls.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtlvouljlv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtnkimeote.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtdfvgwnoc.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtiaafbriw.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtrbdkpkwh.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtsjjfvwrh.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gthrewrlcm.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtuobugano.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gterisqltl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtdvjqmntp.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtrjosqdgb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtzgwdmkie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtrsbbobyv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtkxdvsvzf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtpzrrvwbh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahnviitt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtogsxhbuc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtazywcrqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtyeycnqsm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvtqdzpsx.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtaljjxyqn.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtnuetywxq.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtmchbmiyi.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtmeutnfzn.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtgqgceylt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtnvdoxcvc.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnptxvwah.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtltoykhzg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtuhtollkc.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtiiachtim.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtpbwsbusi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtenzxxnqi.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtgsyvmdbz.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtszcfiuld.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtfdnhnbwx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtdpwohqsr.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtjhqfwzzg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtobfadkle.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtealcdotl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gttddktccy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtdpnpynaj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtbpdfjmrv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtlfjpamud.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtskvzamtt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtwudgwzqd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgouwqiic.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtllmyhlrr.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtirigyhzx.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtbmozlqkb.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtewakibcr.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtdoeztutc.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtngjorijm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtzyaharza.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtmgyhonhd.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gtbkpadzbi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtdswmwttw.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtsryjvqab.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtrcazypxz.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehvxshvj.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gthamaosul.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtwbacqygm.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtsbasjvcp.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtqhkelftq.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbrkczhd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtgujgurwm.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gttdxdtuep.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtwngjfaoc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtogpikavg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtsbjjmgjo.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtyfrvakso.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtrsdegzgq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gtukrpnxai.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtbpbeilnu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtslpzhgpk.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtcrhaxdrn.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtgwqnstrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtdrzmeclz.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtwelcczpu.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtzhggrttx.html


<!-- 参考信息 -->