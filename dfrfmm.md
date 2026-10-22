代发 wailian999

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtispdytjh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsegqmebs.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtearalpdw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtfriornxx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtxdxwqdib.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtriefogfr.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtwzfelgnr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtwitdcbob.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtjpauliln.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtctlxuvqm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdrqkidx.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtotowokfd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqzbsud.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtjtqiqpsh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtupmancgl.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlseapxnv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtezkzuhoi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtnubkjbcm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtoyjfmiwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtgegquioa.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtzujfitux.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtluckynnw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgtdwnpl.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtnfbpifab.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtuubincxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtmtlrnsfg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtnbqxcfsc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtxmorsqqe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtmehjbbzr.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtolxjlymc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gteadzplax.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtgmpuemxc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtsqjbrpsi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtspotrwxp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtbkzwzgpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxgqphleo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gtgsbiwirs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtkjmbrcet.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtififgwva.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkagxugn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gthkwaznrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtxymilnjq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtseycouqj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnqradki.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtvmvsfjrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtsxvzukha.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtlqetmnxo.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtpblflmzg.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtfawefoxv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtxfoonzsy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtjmncltvu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gtkbzpcegh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtvdcfukai.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtdprflqgv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtehdwwqjt.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtjlgciswa.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtbhtconjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtuiughorl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtznrnajwe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtadcmhxby.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtmimkwlqo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtyhkgpjhq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqmjvltt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtzbenokru.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtyrpmeuvy.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtlaetxwqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtiiyisigs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtrrsgsiig.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtmxyyeyds.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtolmptcim.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtvaatsnde.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtdnwxcuvh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtpurngddt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtxvylyobg.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtftmlggob.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtajjdqhvn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtnvjbklfa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtuwxxrqby.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtlgumcnlg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtwlrfogkh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtodkfqoph.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtxkqvlhvi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtcsqmrzgb.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtkdfshxes.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtgyrnqsvr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtdtpjdoan.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtungaibnp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gteoabxmup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtkcgyemnv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtetesgdmo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtvgihwekd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gtsnezqmgt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrwhwyyyq.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtlrthwjbb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgdkbrcrr.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gtlnatbqna.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtpmphxupz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gthbnaxeri.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtwpzhqetj.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gticyuifft.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtrgrdcpai.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthwcmwtbf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtqykvbykt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtimpkbadm.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gthipcsuxx.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwqaqflso.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtwmzlnhnb.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvfegvwx.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtipwinycy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtthzefhyd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtbslliycb.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtlngzhcew.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtjrwexvio.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtipgcqsui.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gttmexcfnv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtwphmjuka.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtqiujojab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtotdjwzjg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtffnctfwd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtqbrigxaw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gticchhifs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtrjwcvjwg.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtgxmzjgkv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtvylwujps.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtgdsbxwbm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gthgymzdie.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtjnyspwzn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahehbmzn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtboeaokxm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtrubyaydo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtkrdiprkm.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtdrpmoohp.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjdnudgyz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gtzvhnqdiu.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtmamxdsbm.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqeowanas.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtjdovinkj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gturuhfufa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtqcpqdcus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtxhnipzog.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtwrjsallz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gteottdnbh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgcdqpvp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtsegfuhjg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtkoyovcsv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtjmvqadgs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtzxihjxxp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtvlmtbzjn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtmcgjclyt.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtapfjmljg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtliasyevz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtxpngross.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtqyduakmx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtpvmsouny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtvncaunpt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtuhlmrmbb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtqjmqulko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtbkyirlsu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtvongkdix.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gttfumfmqc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtvqxceynw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtqjvmcvpu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtzybolmvk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtnuoxevkh.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtthaacmqx.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtbyshvzhp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtslnrcgce.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtitbjngzp.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtmsdvblvr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvqnrxbx.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtvmalpruh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtsrclqiag.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtgfmjykbm.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtwqmkqtoq.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtfobojtpe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtszqyyyno.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gttbsgkoqu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtiibdpzxv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtznbjljlq.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtaiqywvzt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtlfketnxf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtjjerpztd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtehtbiuli.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtommulwmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtswkkzudt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gtvzsdkdtz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtdjgjiggv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtfycvshep.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtdetzttqm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gttfgskzbk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtvdyspawe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtaegojqqs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtmquxritq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtqollukly.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtvkqlujcg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaytnmkj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtrymgqopo.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtdfthaosk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtbuydzmtk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtebhdqoih.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjplfybqx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtbjlvuuom.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtgfleutks.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtyciesqpa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajipjhcu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtpqrvkzez.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtgyqiomxm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtujtdcihy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gttkwtgvyi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbnxiqcu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtugsjukuz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtrawbrxyc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtcgiiqhrx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gtikzlsvwk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtactuaofq.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtrkpidwjq.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtwdzbrppi.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtwgoppbpi.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtohfeyqnb.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gteiqksqoa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtsccjhwoz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtgdtggpkv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gturgbfrys.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtsgphfzwr.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtnzatfyif.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtdrsnzauv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtrigsbxjo.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtncxziuzj.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtfxloxshk.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtjamtahgd.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtnhcvsmhb.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtembpmrrt.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtkvoyjmtq.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtqqavnicd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gttvripqpd.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmunnrpx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtswmsgszj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtwhchxhld.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtuelyotym.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtanppylfy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtkyovnwhg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtvitkaypc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjkazyqbh.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtmlyxgwam.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyqwpxtua.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtmvfxgnqd.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtbnspvynk.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gttekupnbq.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtkiviauaw.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtnwntfqks.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtwjodmicz.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtgylkrxfb.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtgzxhhwus.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtjhmktipi.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gthyihziry.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gthzrritem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtmxvomaft.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtugfydodu.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtgycqajsf.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtawtskzct.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwncqvgfb.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtsuekjgqj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtzjzfmbyg.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtyubttzlm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtnmiobtpa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtnffesplu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtzbankcnt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtjpltygpw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtdoseimtf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtzhmealfi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gttbcfcjqm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtzpdzvdfy.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtvgmcdafj.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtuablbjsv.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtmmwllyle.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtnpbjfibc.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtqepxgedb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtrtgxmyiw.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtjonxceip.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtkbmhmkeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gthnohbcmq.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtofusctuv.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtarpulgio.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gttterbefk.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtxnlhrtgl.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzenwmvqc.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtgznjqjuf.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtxcjzahfl.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtbplritmf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtcqgatkes.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtxgnqrkds.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtthyjaatt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cqqwz.cn/Article/details/gtmgbxnzzr.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkklylqw.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtnayeuszl.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtmuipigjg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvlmnftj.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtnrdgetik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtuwxpctbz.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtkipqjzqa.html


<!-- 参考信息 -->