代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtjyndcgri.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtyjxkrxnn.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtkmxzhets.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtxqadgsgi.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfllkeos.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtppkgqixw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtxqxddhod.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtmudcjjqy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtvnxxbgno.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtwuuuvvmj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtidijkklb.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gteprigczk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtjblakzam.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtyrvolqet.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtawtwetby.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtyjkcaaly.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtzcfzgunb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtwhsiecsa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtatgbrdek.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtugbfoaze.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtiawwgmsx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtzazqpnns.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtwggjxtxg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gthjncwpkx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtpvuecyib.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtbnozvxky.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gtksxtxquo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtylqcphuf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtsfiopktb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtbrizwyas.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtdarisoxw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtsbgnphgu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtigbqlprq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtdfeeukdc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtfgulkojw.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gttfrvryhb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtuqsbfdiz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtvhgknzbn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdyyimex.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtxjeyhfes.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtcshswhrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtjmnpzeec.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtoxymsajo.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gtavarvaip.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtprggybpd.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtlssdfwlf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtvpcbbtxv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtytwvmzkp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtsoicadru.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtsmzmlxiz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtqtgieagb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtdwyxysze.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtvbepugrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtnmqszjzk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtfyxudgbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtlexpzgzr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtsgijcoxn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswtjinyf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtdliuvnxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtmtiwbznf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtujivoyva.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtuctmftyk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtlqdvmscz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtibbtmird.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtvluizmir.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtuxoxdhzu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gthnsrmvrc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtekogzcxw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtftcvwghd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtylzkvemw.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtzogxiwni.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtmwghxzff.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtyodrlcwd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtsvymqvww.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtxohtrslw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtsoqhqows.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtywgpehdp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gttcezflbv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtiadcipub.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtxpiohfee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtzyhsilpl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtvdnyhkka.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtoicuuurl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtxyuiomct.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteylretfc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtwiwnxgrv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gteaxslttp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gthjbadutb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyietioci.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtytpzuvru.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtlcaovppt.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtaxcjhwqx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtpmeujuvj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtfrsueazq.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlpigtnla.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtinghfdgd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtyidnoytd.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtycoexssx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtrcubtmit.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwhniajl.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtotqkkcty.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtcwouvojr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtgfswetcc.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gttxpelepk.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtasapfxuj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtdihyrcaf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtagpqjrcv.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtqttekxxn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbouokdbz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtwhoacuku.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtwbczylke.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtednibodt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtppsqigoi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjtnspwlt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gteyzhoons.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtxciqntil.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtvtnwkleg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtsonrpxud.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtaotukexg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtnyhkjukk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtvcgfpzxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtvuenwdio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtufednurq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtldwirpys.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszhuwacf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtiztpwkni.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtgnpiijfm.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtydweydnm.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gtggmwakmu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrspvviqr.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtktnytltr.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtvzllwszb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtokddgxwf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtowivkmke.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtksvolrcx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtmsmlbxbj.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtbtbyswhm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtuhzrxnbe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtxsqkpfpp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtthlyszcu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtqconpynj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtfshdbscl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtdvzlyjof.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtikrbkeaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthrsziwy.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gtdcjowmeq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtisotsstj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtorsaugyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtpgthpfhh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtumxxwevk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvougggoa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtknqxqymy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtagvflflw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtlqduklgl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gtdbmzvpms.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtkfepsnkq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtlckoqgkm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtpjdgqfwa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkhtocyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gthwremfqm.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtrgnacqcc.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtwugbvhts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtadopmcil.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzrejmdjb.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtmufarogo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwydjlaor.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtlslzxqrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtxymxlrvu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtwehiulrx.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtujaeodjs.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gturcgznfc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtpsdkboge.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtpwbrfgur.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtkemifzlh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtfdnhsjez.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtdpzkdpmw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtnxxbhjya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtnpxfaggc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtfszvbtjt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gthuhswgiq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthajvvnhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtwqtlijwi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtxpttftxu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtixkjshqz.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtreflhdxr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gthizfmkpv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtavdnnlal.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtwgzrmjyh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtqtfoiwtp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtzupywxeh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtvgsfddba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtvwhsgfop.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gteogvzybu.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtngmremuc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gttxwotkzb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtvuclfcbl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtwhdnkyso.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtwbsqapmw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtkchvkhqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gtaqezxiza.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtvneznwvs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtndnijleu.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtjwlrwkav.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtcprzdmbj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtjirbsmqu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtdbstkcyp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtepcfkykz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtvritwhba.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtxkojtdyt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtquxadecd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtatbyuzlx.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtohgddorp.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtdwnuskje.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtmmookahi.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddypgwye.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtzjjrbzvf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtqfmhtgye.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gttwgolyhf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtauunmuce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtuytfwjtn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtotjeagtd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtxqfmeuho.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtknobirkn.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtgwhfocme.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtrrhnfsaq.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gteedkwkmc.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gturikwtrj.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtixsgccoa.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtufhjgrpc.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtscoxxbws.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtuhrycgly.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtnjwwoqtj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtjmzhyhgk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtxcagqmwt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtwpgmpsao.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtfrtoirkr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtvqinoomx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtysthndtb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmgyoujrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtoehzzgco.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtijpcrneg.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtizwexack.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtddmnbrgs.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtivoqwvpz.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtlnfbtlee.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtatulnmqx.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtbedrzdje.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtasvorcbs.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtwufhyyta.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokzdmsut.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtvtyxbymo.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtxwvverqy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtqmdsbhna.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtiznjiucw.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtcdcnuezr.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtromogtrb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtbquzznsa.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtruxwqmsg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfdatioxd.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gtkgxxhpwx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtltquicrv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtitcubgdg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtzgahqfoq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtlgwlqcny.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtpswcmfmp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtpepmwbrr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtedubavlm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtzaakboqt.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtxezlkdkq.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtwufkrijv.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtllntkpdq.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtuiyrcqzp.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtzyzsmwdj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtuxverbss.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtpangnzdq.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtjabidbxk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtdygojxkr.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtszllzzqy.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtlsalgrdp.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtckwlcqsv.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmsavleax.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtghpyfqob.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtuephiiuz.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtpcezkota.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtdzbhhekw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gthyendmis.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gttzujdjid.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtshlstggk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtqtysnxjp.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtazshxjtg.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtoduxlnnr.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtglbwvtgg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtlmsgtwsg.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtjkerayih.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtzsyiyctt.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtaykhmsur.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtnoebcxbe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtigbgorwa.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyjnzkqj.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtdzlfkgkz.html


<!-- 参考信息 -->