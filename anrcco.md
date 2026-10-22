代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2schodobn.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2wknkwyyp.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2rimhdiac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lshxjhba.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jibcodcx.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2zhqbmxst.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2rvwdksqj.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2xaxqbziq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2fktvuvow.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmclgvmj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2dyokxkeu.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2vxotrnhh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2ficroazh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2tkzaspox.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqlydmhk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvmcxlkh.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2dwihjtcj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2jstbmles.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2pivkceea.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2qicbowco.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2dntbkypr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2huoqluen.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2jmiicdnb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gedswafe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2kgoicyus.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiisebcx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2wsuuuzsw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2gfemjkto.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2sonunfsn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2oqaaidkw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2tgknvlxn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2jcpifhjw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2mmawxfcx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gt2mspgnybs.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gt2htveheam.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryakdgxz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gt2gtsbwjku.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2fxobobda.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gt2hnergjmp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wnsfslxb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gt2kpscaymp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2chwolpgj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2afjmxogp.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gt2jcakjesl.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2zligmjgk.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gt2xywenbba.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2acerywoq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2bdsvhkeq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2kmusbjvu.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2nnfntrdi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gaygthoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2caoxpsmk.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gt2plytmhio.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2ickojddm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gt2xajubtlr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2qrmwagdq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2cfazxqaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2dpkmbnml.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewwbkqaf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2hehldzzu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2eqxbpeyw.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gt2jchunxga.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gt2vhuojfsk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2bdewprsk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjecwibq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gt2maermsis.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2yhrvxoxs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2yuejyptl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnxcyfwc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2bdxnobmb.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2qfafdipb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfeddfsl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2nqawuahr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2vkuizqax.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2wvfnesuo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2rwearauo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2rafuuctp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2wtsloxsd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2bajegwup.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2weyhxztp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqgmsxzc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2ckshmfnj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gt2xlcibnks.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ezumpfgw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2hspuccpl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2skyuqgan.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2rpenrvol.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqdxckjw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soikwaou.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2xngmaepu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rxpnpyrk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2wtbncqzs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2wogswgle.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhbzvnrc.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2iwjnskxr.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2bclwxlvw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2veoeztws.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2qoifvvwf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gt2hwqlhapc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ldhrugnv.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2bvxfngxa.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gt2iicyxwqg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpshbwo.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkqpvhrr.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2xgugfrtj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ajgpmube.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqpuneyl.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2bvtpwaxf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gt2kwmmrhzm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2xcfzlmvh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzjpispq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2enfwycul.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opxozflu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2xkquiqfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gt2bwllmgov.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gt2pdqjebxi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gt2yyxiaqcb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2gktckqee.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2vwyqtlwa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gt2acbreqxq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2fylflexb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2rjskzddm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2qfaeekex.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2znxdwfog.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2fxrshlvj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2ydehzliy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2dugfnsge.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdcarifk.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2intmvmjj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2ftsmjuhp.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2pzvhddst.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ronzibvq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2anxwfciv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gt2oxyqilmt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2zgccxqxf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gt2brpzlkfg.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gt2jwqwijvx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2wblhtgij.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2vqokygqb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2budfxsyv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2kpigpafn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2pcxccwut.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2leqhlive.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2ksexrsgy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2vslakbvm.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2qdkklxir.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2usdfedme.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgbsbgax.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2qwkhfcfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2yocqyrdu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2pnsmbxyd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2gyppdmbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2bzbnieum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzjptmtz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2cbmacfso.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2uprcqguj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2gduhpyzj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2hmhmlrci.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2guhrqtur.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2rkayndzq.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2degrprkj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gt2hnmihrxv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2mbydgwpg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2khoqefgc.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2bewkewhk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hxrmxsbv.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gt2bsuyzpph.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2rutizmqa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gt2yfakoyeo.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvgbatvw.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2zcigedop.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2gyykzmmr.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2gzjuewtv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2ixvvlbsf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gt2bdsqrxjl.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwuqgzdj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2eycodyip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2typpjjri.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2hfifoxzd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2sanluvvb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2nchatxry.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2lidbviaw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2buutilqu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2eotitzkq.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gt2wsfnbdll.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gt2pfisssvz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dybunglq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2dmafanpz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2ynavbddf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2qpgajbql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2oqajvmvg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gt2nfvaxgcq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2qcwdvknj.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhfpxmsn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gt2ujvryfvk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gt2namoxfem.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2dunscihg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2slyqvmfz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2victgiur.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2shjryvom.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gt2wdrodlrd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2wylhxutt.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2hgrhgkkn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2ekmlvwff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gruquggm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2mymfoibo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2hegopxzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2zfvqalbb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2htgcswjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2znnvidgy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gt2clraypub.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhzqfqhm.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2dyptbwqx.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2plrzkgmj.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2uzfznffq.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2ygomiqfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2ppuhvvoz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2txnybdkq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gt2ihtclqjf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2ksunkppd.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2epqarhgn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2nddsyruy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2hxqiwliy.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2ckfvyzhw.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2spqzwtsb.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2etldalfc.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekprjylf.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2jjyfijnh.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gt2lnsjrohs.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2skrdqjae.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiyqmdlt.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2rpqtfnhe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2xvwwvoni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2tdcxlowt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2cqvozedc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtnkscex.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2tyupikbh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2shaabaxy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulxvpgei.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gt2igemwnez.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ehksryyq.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2xfvtpdkc.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gt2oftxilwj.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2jvqazemb.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2xabbjvss.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2hqzacycm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2nvfairpi.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2ffigjrbj.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2convmyru.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2ejfmipor.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2derejhlx.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2mvlsdhwx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2fpwwpmpk.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kpqeyfcv.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2bkguedvi.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqmjwjgf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2psfatdid.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2qmiwkskx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2eilyoxeq.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2wsduvfky.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gt2jfzyeqln.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2altqppek.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2wnzfgost.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2cimegggo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2dujdklhg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2ocdqlaeo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2vchixcmk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2tbsdgdpv.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2gugostob.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2gxiilssy.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2fmaketto.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2sfxtikdf.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gt2tdkiidan.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2amlxnvez.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2wbkgscqe.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2pnaeplnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2qkmdcimx.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2byghdjtn.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2yepsyooj.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2hgqcawvr.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ziemmwxj.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2unbjehbp.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2snfanuif.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2fhffxyra.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxxdbebu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2pmtxjvrw.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2tsbpkuej.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2hmlhpiis.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoywnwwv.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2zipuzebi.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2ethuqqrj.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2plbxafcm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2qubtqtwi.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gt2oiujznbs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snfefrpq.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gt2rkqerhbj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gt2rwrqikiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2yvmlqpcm.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2csrrfarb.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2hxqkebbd.html


<!-- 参考信息 -->