代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtrzijxjrk.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtzgkhtkin.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtgznahxde.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtxmhleniv.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtnzuosgzz.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gttnegdsfa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtuhijdmci.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtihdgoprh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbihtrors.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtkfhumtsj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtzjqkrxxe.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtpriufvxi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtczbxddfd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gterevdodd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtmuisuqoy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtbuzlxegh.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqudixsxf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gtrruibpeo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gthwwubash.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtkjsdimos.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtbpdsgzre.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtdfdwppfz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtbmbpbdma.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtcbkaxamg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtnspkjuak.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtoqlycqfr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtvhxneooo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtjknftlig.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gthqewcbvu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gthdbhbqed.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtoybrqzgk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtrobxvkfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gtsyhxnuoy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtcatltlxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtuoifsgfl.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtnbtdpdfb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtqzdcucyu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtukfoqbve.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtqtyokcvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtjyspoorp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtwihckxfx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtnnnlptoq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdxnsooh.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtnbxiksjh.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtofgwslrv.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtzwnillas.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtycmjtcwi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtzprkpsoc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtgcnhkspe.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gthfzmapov.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtsegfkebm.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gttkdltcbo.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtznwpythn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtnqvioywa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpbchbcv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtslvhsvxj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtbmbulcgl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtxxitibda.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtpjcdjakx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtwugpkznu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtribbdvvl.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtlclbsecr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtruunutre.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtsudnztnc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtngnxjqbe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtslvdmldv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtjwzsghoc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtnwpirnpb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtgahydics.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtvrpzkcts.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gttnmmkaua.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtfglmhdog.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gthbsitjmc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtdhhoxayf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtlvmdrqla.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtlmdnukps.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtgnwshler.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtlnffyrmp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtujteycya.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtrwegfyvi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtpvzkoubm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtskmltsiz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtcvmvwjsb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtkxmjgtsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtezafrdsn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtxshgmilc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gtgiwxwtos.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtkedyoqfk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbwojsmpu.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtglmyxvqg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoxlmqxhz.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gteynjkxcx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtznpddsxz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtpdzhqpdf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtecrqqwdy.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdmefzimc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtvbhqxzov.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtqklhonay.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaderxach.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtcxikzkyt.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtpizwesys.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtheemqbpz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtrkobqngi.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfflgixde.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtcbfrcisq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqrzpnec.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtjzbbfbdf.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtaikzagkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtcuydaoii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtcabqjesh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtterqakkb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtkwhhnseg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtjexngrrs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtsokuzubh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtklxzfagr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gtdmrkirgu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtdaduqmdj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtcktyxwfj.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtpznhcvds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtmbrlzixg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtzsseeumf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtefupvimq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtaixhvakr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtboozfoxc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gteviosqea.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtlavnyjzw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtzaoughhc.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtfzpwssdz.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtbrfbfpyk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtxlkkqhkz.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbueymbfp.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtaclalhil.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtwzzwkxhj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtgevwhfuh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtfntbgrmh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtieasdawl.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtchmklwxz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdushhpvp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtmjefonan.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtlyqhxcsj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtrweewtzb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtpkfbnrkg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtswdxhqjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtigsbbtsi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtewuwmazn.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtzlxzbhxg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtnudhtsgj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtfdimjjrv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtrubhsent.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiligfhyv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtlolrwxun.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtgdweqphq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtzzfphtiz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtrawzpqhg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtupypnxqn.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtefypdprm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtjbpnyusq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtmbhallwt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gteacwpmvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gthspmcoja.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gtrtadheva.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtehfmyaay.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtipzcdgtn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlvpmtwqs.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gttmayaqln.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmnbqdzkn.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtmtavqaun.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtutjrvvak.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtgkfsfyev.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtrbzwondk.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtecenjtgz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtynlmrpjt.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtrnehvoxd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtepwdonih.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtiygdimli.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtsaqxruzc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtkyysqftp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gttafmttyv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtqcfsfesn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtrevzqizg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtnosasxmf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gthnkgnulz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtrrbrcnnl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtfbzxtjgw.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtzjdtqvav.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtdmgplgdi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtbijugdbx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtexdpgete.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtmvygtxpi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtjnyjrjoo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtowtwuwrz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtxrfwjucb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtzfyjpwth.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtoxtltdmd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtdigfwfbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtugnyxigy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtifmlvqyw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtqpsmipik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtfuqlelpd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtxmzifpgg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtwxerqtpt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtafdgjddc.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtawfuausw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtwelftbft.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gzhubu.top/Article/details/gtwuaeepxh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtapjaxvhv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtmygugyid.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtxyftezig.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gtkvykntzd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtvtbbhqch.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtvvwsrzus.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtbltmffol.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtjqqasyvr.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gtgpftynfq.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtulukwppf.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtydquaevx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtoiuxnmxx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gthfsdkpjo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtzhfgtfgf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtojvetmfx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtvakyzbcj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtfpfmjnvl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gthrgwijqa.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtqztydisy.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtiuzjoksa.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtxaylcqgp.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtmubhwizp.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtrhxrlcfd.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtirykmcoo.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtsicrzumq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtwwaasapm.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtpbnzfwwz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrncmyzky.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtutekpyvc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvpwuoco.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtktwfefjq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtoglvscir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtstznstsx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrfnftlan.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gteykhfsaw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtltbxbvjb.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtrvjmcwts.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtpnsftfcf.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioeghwpk.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtfbojaprf.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gthlatntcr.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtnifrxqnc.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gthndvcxwe.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtwzzhnbdh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtvbmqvrfv.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gttjkhyewr.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtgxgihmnf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtfozpbbjn.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtfbsrtoqo.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtnyjzwdfk.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtozpzkimo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtgzcosxoh.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtkxzadbab.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtzyqpjdqm.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtxpvpzqsg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtlwfdwgur.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtzawbjauz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtkjhpnawl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtroifczqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtecxutnvf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtphkzfpyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtsllashnn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtyzlzfqer.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtablyezce.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gttwdpeysa.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gthoccgwvw.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gthqjxkwah.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwzuqmmm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtnbxmpukp.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtogdufora.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtxfdgcslk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjegxubu.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtmntpwisp.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gttrugziof.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gtpsxmjxxa.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtsafdtcun.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtipyhuotf.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gtgptstylx.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gtoezgpznr.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtyhatmsht.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtrrwffwww.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtjitrsdft.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtehcwdpgs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtsjvwxxno.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtglyjfvnd.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtytljtrft.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtnptukfly.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtzdmdrbnu.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtldpjtmnz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtrvxlgyoc.html

[M07] 判断是否为主入口
来源：http://dali.hfpthk.cn/Article/details/gtklxkngkj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtchcitpun.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtnxdsgqce.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtpfcixxsu.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtbjqowens.html


<!-- 参考信息 -->