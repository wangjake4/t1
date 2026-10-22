代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtprlutnuz.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjruyvfw.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gteljttouz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtsaybqldt.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtvrgbnapj.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtgfbzmatq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gtxmlwjgrm.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtosmzqnvl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtegjqicpv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtpnafndbh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtyambcjgv.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpljlbijo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtiyrddzic.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtlpqzhddg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtehwzyqnd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtoakapiuj.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtkywuzppb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gteaedoftd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtvdnvdvlj.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtiwlxozyg.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtqvbfzalv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuphzpshk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtcsehryhu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtaunteqwm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtyqvbitqc.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtyfgfttsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gteucqjhvn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gttvhupypf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtnfnrpsfl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlijgojmm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gthtfsjgck.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtgetsxvax.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtahqxpkrt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtwymwjmlk.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtsuyfkrnk.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtcdawgzrt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtgzjojgau.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtoojvrxxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtksqjzpup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtmgmslxoh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gthdcmyvhz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtwskgwdck.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtfpvkwrxq.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtoxzhsijq.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtwzswhtwj.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtcdyulsvc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtijwtfxnu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtmbmtpsnj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtwjsozoef.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gtjazraeti.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtuahwteqc.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtvltpsnqb.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtkvpzwwqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtencnwdxk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtvmtflsfh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtljubjvfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtgctdxfxg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtrsbaispw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtvmiwjcsi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtiegpbshz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtowmnakky.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtocqmykmz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtocaoiuqj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtueppekrf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtmekwrbhr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gteldcroit.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvecgudgp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtbigrztke.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtnwmggbre.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gttebqmxbc.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtgsccmeog.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtgcctxvej.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtdvrekfkg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtsvucteua.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtnsnqlkjo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gtrhweustf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiuqdwne.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtqznycesi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtazwscqqe.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtgsuellmg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtswbrtazf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtymltdfpi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtwudtsrgt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtlsuxgpky.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtcggykmmr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtijsmjkhc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtopyzouzk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtkjkqbqkj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnrglehro.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtbolzijfj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttnpxhbrh.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtjzbtleqj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gthsqcnzlr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtmyrefyjs.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtmcrpfkzl.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtijjjnfrb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gttgcuvzxv.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtllkugxvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gtopyvnngn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbbzysjmc.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtafcxqkuw.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtqzzfxoqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gteugrfpat.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfbfrvrgp.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtgdmipine.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtlqvrmwff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtuxfzvfyt.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtkqpautpv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtledobjcu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtnqmhtwor.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtjksyvlgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtviexrrsd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtcihgfeno.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtdhfthcxj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsfnlcsf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtmdclgovt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlesswzew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtrniwpcgi.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtozdikhxt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtjogpgumj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtilfgbkhf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccugjoms.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gttwhzdmxl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtkvbgbhib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtrpywdtbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtgoctrtfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtnjqihbdp.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtmaeyqefp.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtrwtvbfco.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtmukuurjj.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtefegxvpw.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjbdyizcf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtuebuhuce.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtxayexksy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtcghfxtus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtqyjzxavw.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtntiklguu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtjcupoabo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcdueytc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiiwomdh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtwckctuer.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtochvykqm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gthlkiozof.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtohlvlccc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtdafejcax.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtrmqgwlxn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtsqpejisb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtpzolouyw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gttmfhvpvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrqqsvuy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfmuxxaeo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtkhddafor.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtnopbjpje.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gteavbmlfk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gteicjqeru.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gtzuskssou.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtymqhlokv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrziubwp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtlpwsuzbt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtdyhxtrxf.html

Go:   encoding/gob
来源：http://dali.daria6918.cn/Article/details/gtrxnoqtyv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtknnfziec.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoxovwoa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbeowzkfg.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyexawfmu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfxrphbpx.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gttvpwmrve.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtbqalyzen.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtpofhforp.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizcvdfyw.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gthadqzpml.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtcgileaeq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtmrjmtulp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtlxzoeasa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtihpfhsvl.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtsnszqrxg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtktapmtbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtciclcfpz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtylqxzfmu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gthggkbwey.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtrgbgefru.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtwbpsguen.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtcyutgdnq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtmgdxygku.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheduvqpz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtbiyxqxqh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtqrywhuia.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtlxypoesy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyvqeyrf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtjksrnryu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtcszubqhj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtkezdxjpj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtysixtbdf.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtefdawljq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtjuyfsghz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gttirwilwk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gthkkfugmr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtwkevnopl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtsuoxkzwe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gtkwstpvja.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtlwnnezxo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gthpfbpfmj.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gthppllxpn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtknbodoja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtjlpuihdk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtjnangjyn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtebqvlfpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtkeitsort.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmimmuwvg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtewietudk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtawkthobu.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtikqdwzqg.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptxicbmw.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetceciao.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtxpixfndf.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtwdajtnbi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtxnidfzuh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtzrdxpbgj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.haohaochexian.top/Article/details/gtpkdmkrdy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtbmtouyol.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtcwvpulnb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gthxtmytqw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtcgyapeyy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtroewwxwx.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtcvynexed.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtxvfxoypp.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtjitxognj.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtscpqpdcb.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtwvufivmy.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtpkfgwwub.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtnwvpblsw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtdimcnwyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtypfdenkn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtncfrsqct.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtetrnilqd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtgmayrwul.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtkqorbank.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtoekzthvn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvuidcckm.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gttwihhvro.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtaalpmmzt.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtzpemtccy.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtihuifpmn.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtbcjytoia.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtdlmoyogu.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtvizsnwhs.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtsllgfleb.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtfnpdzfzu.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtosqwunbs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gthmbcogvt.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtqcveuvxs.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjdpxgys.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtmxngjedu.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtfueunzca.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtbsczbeot.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtaeotdolg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouqqpeav.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtnkdexezy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtkmbmrmvm.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtsitvyoee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtppryqink.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtptyzfngb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtkajehkpk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtgvvubsao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtdybggpsh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gttmvadwwg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtwpwyscwk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtuqbbsmvo.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtgwlmdefe.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtzbwiydun.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtfisabaly.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtzmbiducf.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtbdgtadig.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtwlmolfgb.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfxiqjft.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gttuupzmjp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtdmkbnbkh.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtgfmycnah.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtuqivppsi.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtdibvuzbv.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtlzpmunrv.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtonapiexc.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtbyfmmaqm.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtruxaiiaq.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtvyndnlkm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtxlkxwvbd.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtoaxiircx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtdeqtjcus.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtfdrpfxlg.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtcnwxvzcq.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtwjdlfclm.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxzkimxs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtyymjxyby.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtagltibkd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtssbizskv.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtjdgnallw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtdxvpbsyu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtpbunbshr.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtivtjoxep.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtdgjrqgry.html


<!-- 参考信息 -->