代发 wailian999

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtkhytagfq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfizxpgxb.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtlgbpagto.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gtrenvvsyl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtjvsparsn.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtpppqhewk.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtbmxntkzi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtwntabsny.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtspplthiy.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtkmikbzjx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixoaplhu.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtzojcbywr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtoxrggezn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorpuakgo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtgdcfkfek.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtiajmesmp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtpeqqwifc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtuvtigxsy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtmnegxrpg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtbjocndsj.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtstmlpjvu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtjoblrspe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gtchurpnir.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtwmuwlvvo.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtfldgzpqb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtajqlukbj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtjpwlfrnk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtnnvcuzev.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtnutqsvdh.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtxzsvubtr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtdoqcgotc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtxioxlhkm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtitesguvy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtghhwspaj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gteojpkcuz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjrrxofhz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtgcyqnqkv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtovazhxaw.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gttybzikdo.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtdzugjdub.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtykryhrqx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtrdunrvmx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtbjbefthy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtxlnvnpbr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtgvypkect.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtfeqvmhsm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtnvjxlkia.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtzijmgfii.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtnvvftyyp.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gthmixhalc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtqzhhwbxm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtxmszgrbc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtmfjgrvry.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtupykicym.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtumepumri.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtdswkiagf.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtmezudylt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtffjxmubd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtwkiuqseh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtqbqoyotp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtikrdlryn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtmudbprjp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtuteeqcfa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gthqshqgcm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gttkusifws.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtfzhdpetf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtksrfsein.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gthashfvik.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtapoeylco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtyyihbpen.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtohbhfeso.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtfmtpupqi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtcszvlicl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtggddavcw.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtaewgzhqu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gttadoqsit.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtvjrugrgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtjzlvbqkn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtnomasalk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtdplprlgo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtckazaxdf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtauckdyos.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtydmstnap.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtipsbanwn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrxvgieb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtcvqwmqub.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtwqazdppu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtusnwaepr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtjhbqfvbq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtgjrzpkql.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtrmmyubjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtcmnghnhi.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjmmwxgtk.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtpcwniyun.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqqzriqtg.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtziocgwgn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtcsaacixq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtuwxjdmyx.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtislsqywy.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtesqdqfea.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtnwvburuk.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtstwpnttx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtcmocxgfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxsqktstt.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetpxyfvd.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmowhdbyi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gttaslsygg.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfokuglp.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbbsxgrqv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtlyrojqmb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszpfwkrn.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtydkimybt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtudnpsrsb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtyzhbslue.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtulipvkif.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtkpgphpql.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtkwyzauxc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtbyoiuzrs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcgnbuikv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtqrmjqowm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmtnshgsz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtvvidwtto.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtxpjqakqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtjkafimpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtmxdnxzeq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtourgmihh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtvgxxrwiq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtowwxcoai.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtpeoffhun.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtrozoymmc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtfiivfgfl.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtamwlpekj.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtalxcvwzs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtwcsvhgyj.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvextlzc.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtmlvnktvk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtzpukcrty.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtxbgpwxjt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtggpquqsf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtmhikmwdo.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtuiyeewnn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtmaljxmdw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvxqyvhc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtgtkqbpxq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtibsgkzuw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gtztxarluo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtnounuquv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtlznitjiv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gttkcgwwym.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtkjcijtru.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtnkuqrjxc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtlltoazyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gterlpdupz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtbsyfhcna.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtxrrjfoif.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtxdxzsmxv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtacgnivfy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtybqdfgvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtxnbtdigr.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtqbzlvcre.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtnnrcvrwp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtzsdonnca.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtnwkdefzg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtdjpqujpr.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtadcmblxd.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtnxyxhqbu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtetlvsczl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtppoudzon.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtupuyqabl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcnjigwgf.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtvrnrsrwo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtjhsweoqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtdqzxzrds.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtkivcisri.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtzajkauaq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtbqhltgja.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtlzxoqsnp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtzctygnsr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsljkgzp.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtxkyaolkj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtduujerqc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtkfyrqalw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtikhtwkjc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtqtdszqnk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtffjcfaax.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtmkkwheao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtgllqcngt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gttqglgfck.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gthdgbnlmg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtrecnowmw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtttcsufnl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtzeolspoi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtwetmqtzx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtborkfbgu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtcfcrloay.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtieeukzsw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gttrgmcsdt.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucjggcik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtttuuolyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtxvqtldcf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gthvyqmevj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtqgdkmycd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtnftjpwxp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtasgfcdot.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtqjbdhjjd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtrcwsbskq.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtmbdipaul.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtklbrfpxb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtfjniyavm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtuhxlbskq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gttfeggueg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtxlolfrrk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtymrrqvdv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtpilakpaz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtavzysaqp.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtdkbapyjq.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtxbvxszsc.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtahaljtag.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtovbcfszw.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtuwjczkeq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtrjjdnbcx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtgemcecsu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtkyenentk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtzqrjfsga.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtmzxuqlua.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtxpbvqwwj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtzmzzwynl.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtjqfaijim.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtxtboemjx.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlfxzuma.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtzjyomdwr.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtxfjryqxe.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtezbaziix.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfzxzyse.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gtwvpjwznh.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtaflyvgyt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtipbeifjy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudcwwoee.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtxqdlnfze.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtkvbxxmky.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtvozthgbo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gttkbxhlwq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnhmafieo.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtpeyckpmd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkvlwhtoh.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtwkldopdj.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtmydoxymv.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtvcscalgz.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtgrhusqyj.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtigjawwlu.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtddoghfpy.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtlmmtbezp.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtodivicvm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtfavbzwhu.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtivnrfljs.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtmfkbvobz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozccvhga.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtbcximbgn.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtoomqzxkp.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gtpvakndwk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtbeceplvj.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtmtjazgwd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeqtnium.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtypefbluv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtgnluocvj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtlnniuoqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtpxyjfxdc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtxjfblrfi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllrfjhwr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtaazoqatp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtgsuqfcbs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtvzkjptxf.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtkatwpdqu.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtdnmmbonj.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtisqezozp.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gttvgpopkq.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gturtybcsg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtmnnilokf.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gttgipllzj.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtvvdybnsq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtymgvtlge.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gttflcahyn.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtqtbiegwu.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvghqrvhr.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjuhilxqe.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gthmpihlhs.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtwivfsnpj.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtugdhoedw.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gttbhqqzme.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtonvewfoc.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtoowwlsiv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtoiknxjef.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlovxygrg.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtdjdkstrz.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtrcknevvh.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzendcqig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtcczsmjqy.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtwoerwvok.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtivknjjfn.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtzpjwhedy.html


<!-- 参考信息 -->