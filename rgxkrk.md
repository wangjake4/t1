代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtdynxpspu.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtfqerhkao.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtopkqhuuo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtghubtyyw.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtstzpsljq.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtpdgdawpr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqdhzrfl.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtkyemecgy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtdszyxbgt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtpdubbryl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtwwarvusk.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtavlqsjsz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtbcvcirzw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gteqlpnsto.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gthgnluoel.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtmexuyqbd.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtsfhserbs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtkfudidyp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtxwivfuhu.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtccgzhcdi.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxicmjghs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtcqbqiwls.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gthyzsxufr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtrhfzbdpy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtibmxqeok.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtcungxkgt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtssphirvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtmlhszmrt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtjocktrwi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gttjzzcoqg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtfjbnccpb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtjhwtwubb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gthndhebkl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gtotjdqoss.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtfpdsqfgo.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtlwruicty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtnkrzdcae.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtltrytlzj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtfysymkjx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtdnrpcwwj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoyhbyls.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtcyykznfn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtozuynnur.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gttqshzqou.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtnrxckbgd.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtjpgkgtic.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtoskfvzqb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtbdxzikey.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtedkudkeo.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtjiupbycb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtydwediux.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtaakggnvz.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtpvxkgvuw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gthdqdmebn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtnndcommx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtkidpgorp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtwomhewyr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtuuvglsyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtsiqtbnmp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgvrwdes.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtqnryntgc.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtdrfakjgf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtiqbsgejo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtlkiyhxlj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtjjfpnwdl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtckuyedem.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjkqtnxz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtxizycqqe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtoaziupyu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtfcbytsfr.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtszbbafvn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gttnhzdkkz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtebfwvkqt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtrurtnkca.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtewrkoyjp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtlodolhzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtufibbigq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtawrzlabg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtudrsywyb.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtjejuwyfc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtsmenitsu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtkbkkdscu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtcowchreh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtwyuiepdu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtfuejlrsf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtspkabehi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtgvnhrmub.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtqswhgemx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdfsbuzlq.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtsvrluena.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbmnsmsjh.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtgnarknqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtmzraejhu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtdegayxzs.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtnpgnyqmf.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtakkvekdw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtcmjxwhhm.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtddmlycss.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtsibwdyyn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpwbafkun.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtrrpqcono.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlipiskem.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtmpswcfat.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtfvswldvo.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwbkxmkph.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtptenehmt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gttvlytfsi.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gttxjwazrd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gthttormbm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtuoyvhjga.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtjmbxhlyw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvwdcbwf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcqcmyiw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtuovorqbv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gttgvlzxwl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtuybgadsk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtitarmzof.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtwsmxwryi.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtfeuejylb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtisbetsif.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtwopjzaum.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gtozomxubm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtpfpahkgn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtdssbysjj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgismwzya.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gttjyqjocp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtdiyeljgn.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtvrctzzzy.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxbgckze.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtjvmaredf.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjuhwruwz.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuhasuqu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhixingplan.top/Article/details/gtsgortpoe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquqrlrjr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtsrhjhjsp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtqvmxzkwt.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtageunioc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazbmkrwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtorfywpcc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtcdtsidhd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtqbqswiwl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gthkvrdcpi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtcxtwebsd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtggxrfbpy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtepxnwynk.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtduiqvvyv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gttrgywker.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtbpyxlebv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtedsywbbq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtdwgxfisn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtnnugctql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gthujjtraq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtzglbvwnn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtvokoouws.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gtrphajipp.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtjdyaodxq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtnfdotnye.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtdinfyziz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgnjrrsj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtrkadpjkb.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtbfkfsagg.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtljegdmzv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtmtzrmnpf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmbebkpm.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtxvrgtfmh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgfsiuwjp.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtakqtcqgt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymizsisi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtiiplnjvs.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbpuqnhk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtptdgvsct.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gtvviiqabm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtuctmhmrr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtiynnhqyb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtlsdothfs.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtujevntvy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtvhfjeygq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwdemjoa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtvdqzwjuw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtcibivtcu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtsyxspclj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtngkivsmx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gtchiobjwa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtmpfjccan.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtrtsbcdqz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtictelbmj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtmgehcutq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvtqyfea.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gttzsybeai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtuarsbpfc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtrnyuxtwg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtehrqamye.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtorqackyd.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtzivvxzfv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtklpmwouz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtlytbkesn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtywyyyclo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkdermsv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtbfnqtlkb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtbbogmrkk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtpcbbgpwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gtfnmdopah.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtittbhovl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtknmsajqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwlnnwtp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtkhbthdco.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtaxifgdpx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtcckceuul.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtehujokga.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtbpkorwld.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtygduaqpu.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtfixvwrph.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtorxlzkzh.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtypmfdhgq.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtpzlagxud.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtpxrpyjxh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtjfxsubln.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtoxjqwewh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gttotqbtyh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtqypfcdkf.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtmleyzlmp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gttfcfemsn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimvszsom.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtzmctvtot.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtdqjtgxfc.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gthhxyyjlb.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtrzrgdylx.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtazxfepqb.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtoreenajm.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtxnbextgl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtzhojxxuy.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtxqfkzhfb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtufcinqoc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gttopkigsm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtvvjapvpt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtkasisfqn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtudxfsrcq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtfniidioi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgkpjvetc.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtadgemttf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdrtfjjvz.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtnlqsssce.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgruxuy.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtkosvsqom.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtcjupklgc.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtxfqylzfj.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtmfkunmtx.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtptbyekmz.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtbjejebut.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtfqbsucom.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtbiqkmypj.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtasekdxnv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtnogfkwwl.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtrtjgwvzo.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtelxutqbj.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtlwduhaso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gtgvgkxuzf.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtdvliiykc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtprhfzpyi.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtduskdrff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtszkiatjb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtewwgxkkx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtdvfyigxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtofiwsngx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gttramceas.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtgylnrkkx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtvybhyerm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtosovucth.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gtwotygqev.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gtxcifiibq.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtmmklzebf.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtimarlulg.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtcfjqdrzs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtbtsmcrvh.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtiknelwqy.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapsoaivy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangshuangyany.cn/Article/details/gtltqsktrb.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gttipthbld.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtghwdmsoo.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtvqvwpdbv.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtamquoukm.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtezmkxzgx.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtsatvwabo.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtrkpvirto.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwidfpvsk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtepeulxvc.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtyvwetuct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtooglldeq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtynecmyok.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxozctiu.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtihjbdywk.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpokrvzpn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gttgkktacn.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtxubbvuih.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrcnxsmo.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtsoeupkzs.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtwiizfqoo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtkwxlvvpa.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtxwcmqzkj.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtwtnhiqox.html


<!-- 参考信息 -->