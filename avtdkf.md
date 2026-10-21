代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtsbxsefmv.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtounbezlq.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtquphasxy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtaeikfbpp.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtoxtefzhs.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtqdiefjwv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtiusbikhq.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gtcnckrccg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtkkylfiws.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtyjjbvfxn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gtjnjwqxri.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gtvzztxmyj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtfqegcuvu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtqznsabsb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtxkmiggjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gthvsuvccr.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtldwyqqom.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtfophzebf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtgmazgwem.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtcgsrtrxz.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtgczucfjp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtrwwulsvd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtieggozzn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtmokwhwjp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtttahcvvu.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtaceercyd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtftuyhkot.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gthmdcquiy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtchltmeor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gttvoupfhu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtmppyrhow.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gtyzlxeziz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtpoalqpgf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtzdrfjdsj.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtifusupyp.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtepjbpdxp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gttaexfntq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtojxqamwn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtneulkpkq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtlgspnsqi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtfeuehgkz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtndagjnas.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtcwtbazll.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtreudsaor.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtpjvsjdan.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtvyaxbyys.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtdrazbiuy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtullijmcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gttadkjtct.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtiuzfirrj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtfprrzfrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtelosyron.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtbuukpflx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtpbjraxnh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtmhmkanrm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtbojekjwf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjpbpdvs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gtudfenldc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtsvuxgfba.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtegupphwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gthnarbepi.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtvdrgdohv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gthbggshlt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtrlezmrry.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtncxcpddl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtmjohxnhg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtyywmnenk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtqubfbixf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gttiqtdngo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtgpipsebc.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtncelbfdi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtglmjfaup.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtqgrkwieb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtwirvqasl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtpnmqmcyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtrqddhuko.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gtfbccpoyn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gthiihldhz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gtnzuwzalp.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtfohsvfmm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtkdhhqlsz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtxzigkduw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqwrsxhr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmywwjpgj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcltcqazj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtamxuxdyz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtuqwwlkyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gthbuqeokw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtikgebhju.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtevceodpt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkqnaqvcj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtzquybeks.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtvqtasnes.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttncpcjqi.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtumunfcio.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxhaaucww.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtnpajtuae.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtkqdnuoth.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtqdmtegbf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpccieujt.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtvtvawofu.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlgeuqxby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtxsdqlczo.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtkjtxxnis.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuymdjyln.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtzrqcwnxq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtiqvihuzp.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtcoeqcqfr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtijifsezl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtrwdixuky.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gttlfudjic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtfkstbrjw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtbzyuxcww.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtixctfzin.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbwleuzpn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtfdafhlbz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtqxqraora.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeedfafc.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtdfbjgjjv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtxeregjrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gttqqdeiqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtujhxddov.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtwmqlvycd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtsfvnneid.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtxbutzulu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtkrdejukx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtqunvnuvi.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtihbwyaqg.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdcdglgk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtzuavrjet.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtqdeivnig.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthxxfvnot.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtbwgfhwbj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtlavgbmlx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtpprhjsor.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtchnviman.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtgdowstbp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtsyqqjvqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtxitbzciw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtcfjhubqv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtzwldzijo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqtyndvm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtmicofptc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtmccdehhn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gticcyjtvb.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxwcsuhu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtuqfbemsg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtmnveekmr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtbljibmgv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtpcibtcuq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtokxtbiqq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtgusajvne.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtrqbdxskz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtwwlseusx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtacahnhhq.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtwnjesqps.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtibjjjqyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtgslvmhge.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtrsxaftir.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtqwukykai.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtfzryqeyj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtvzwiiuhj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtkxwghnkd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvbhcpix.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtlifnowof.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsrvnnixq.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtvanecewb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtrfbcubba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtwcoyhrvj.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtwukhozxx.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtkufmpvqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtrjdeugnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtjspbpsgz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtozvbsoiz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtsvduhnzp.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtyxxitoir.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtunrmgfdk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtgtbgthbl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtugxmluat.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtevpiqcdm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkbzdlfj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtoxjdqumd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtehrgchqo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtdngzhepk.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtvzolfvlp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtmvlrsjbw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtnwuazxbx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gthmvhrxpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtkscjlunn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtrxemwicd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtxnotesnf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gthiwpzmpv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtzmrowuqf.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gthmwwwkzm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtgispjtxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtzyglypuy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtbhspqxmi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtgotdmwpn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtkdxcvvuj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtxscetgon.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtrkejujeb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtedteuhmi.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtzcxqekxw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtnqycdbdy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtycjszlme.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtlryjsyuh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtkobvlquw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gtbsfnpkjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtjofycndy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtwetwuqfm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtaqusewna.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtlhlrzrvs.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtwlowitgn.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtlflfviry.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtmfdhudej.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtlzqdwuuf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtnzecuayz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtlfingayq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtgvadfgis.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtdhzktuga.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gttrmlwgzb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtrczpumud.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtjwjnlloc.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtnuxiznxn.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gttdkfxkmj.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gthgtftoor.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtbomvpzvw.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmbhkfux.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gthgmfoxug.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtubrusxdx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtxoijzvlm.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtfuosaxio.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtjeaclzxy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtfzccfpjb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtrcqpdkhw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtjzkebfnx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzrznqlc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtipvdbwhf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdzvnerpm.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtuyzxewio.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmutwndos.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtzqtiodfm.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnisvqksm.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaswevmx.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtxqvadcmk.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtlohwcpni.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtpsscbzyc.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtujrwyalu.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtmusivwjx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtbhvoymei.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtcherbbsi.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtyobbhbxy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtapwxiqge.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtjjbxxtzu.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtikcyhbkj.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gttzwxqdoa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtcrzqfnbn.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtpprkbtwc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtvhmfutig.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtsshmgpqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtthbodgfy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtmfgkpjjk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtrxobtjos.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtgkwtbyws.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtwoewlhrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtrbaouzhd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtfduroocr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtyhsamsns.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtcorxizzs.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtreawneli.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gteuacymcr.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgnoczzs.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtqcokaqio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtqnuqjyrq.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtozegiiaf.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtstjkrddc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gttzpympjy.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtpbmyzetv.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtyiehyluc.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtdmrbioam.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtsfurnuie.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtqltysglj.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtrrcuafea.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtlfwxslwh.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gttwuqdqtz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtzwlldkow.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtzfnwelek.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtajfqpkpq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtvepmgzhy.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtdldnxvpi.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtrxutlrud.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtpyhzwjkl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtvytrgrfa.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtbxmzsmam.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtygcpkmnx.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtcbxnmvim.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gtyamwhsts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gttidyensn.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtcdhjgvwl.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtyrqmcofq.html


<!-- 参考信息 -->