代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtggikdqcc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtefsmgkxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtxhlfxpgv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtmboyhped.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtzgudlzou.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtwzwpctsa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gthzpnnpid.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfyzskfvx.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtnlnqguit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtldcafncr.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtreqtmixi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtmqvtdswi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gtxvqthnnr.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtcmmisebq.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtyikmfxud.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gtfeaafxoe.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtconasyun.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtvyprqfgd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtujvjdaqq.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryolucdq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkqyqclw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtmctwaojm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtmjugzhzd.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweblxewb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbioebjjf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtrdqksefz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtqpdwguri.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtddtrdqjp.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gteueljyeo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtrntkzuig.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtzmmwvzze.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtqcxpwtdr.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtxmaoaxqq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtsxehkitl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtvfhwkytt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtmjztbcrm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtedyhefbq.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtqlccwjpb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtfpoxqjgz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtmhkjugup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtdypiwkcq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtqvtjfigs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtcnzmulwf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtatpdjosi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcyfbocz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtydysfhah.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtchnybikg.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywyarnbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gthorziygy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtibtgmdlk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtnzsklgof.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gtmnpavxom.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtsqgyjrho.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtopzeknag.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgytwmkrm.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtdqzehgth.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gttxigisrt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtwpjpcpln.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gttintssym.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtzdxaxzta.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtbyqwhtyh.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtelfntqoy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtbiemvvwd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtqumtvfyn.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtlorsjocj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtogatwzfa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtptjrvrbb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtvdlwcmpx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafbgdxgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgnknggzt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqnjzcoqj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtwnoehgog.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gttcfyonrc.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtocbmxmeg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtneawaeub.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtzysblogl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtotplnsvv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtsaachukb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtakuosbfn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gthzuxalil.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtsspjxsih.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gttvbkpets.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtxlnfjptm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gthuvtdkrh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtueqqhkxe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtzgdmzkef.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtkzxfpvoo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtueffojty.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtaewzidnf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtnfaftekk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtesmlnbog.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gteaqgkhfl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtherfepyk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtowumabiv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtpifvwvup.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtaryragzz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcajhxzfg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtarhpjunf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtwfvbrmnn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtkugmguqm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwivndmpb.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtwgenuigk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtczkyklrb.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtzbjaczqd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtokysmpvk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtnadraovv.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtjgjbatnm.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtwiwltaol.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtneddinga.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtzcyhuynp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtohutlkey.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtgakdsjkg.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtherpqbgb.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtsjcgfstb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtiuwtfgie.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtuqbnmxbh.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtmljcxkoi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtyoayuyyf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtofkvfbuf.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtqcteaavw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gthnjlscje.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtkykergty.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyknhpxcp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtgztblmwm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtjyqwufll.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtrtdxsavo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxrenkttx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtdzhvxjtn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzemoeuxz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtbmzffcme.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtggchulss.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtzrhqkuqe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtbeifyvuz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtenhbgdbi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtlhmavobj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtdlnbwygp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtnzwfldwi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gteuleemco.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtjxjlqwsk.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtvgcnpfkj.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdnezikhu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtklsgijvc.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxywdignu.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbfatkaxb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gteprcoanz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtmfxbzqeg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtfrtmeiqr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gtxrkzfogz.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtpupujmxt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtcafhagre.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtenkedxxv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtlpncqhel.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdjmssjpo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gthhrelspv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtxbuyaeoa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtagppbget.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtyeplfqlj.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtndkdugmn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkblzydax.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtmepptdrv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtfytmoocd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtpxmhdhrp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtcyvxqmvy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtrgiavfpe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtepyegynd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtjiqcnmem.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtmminuzoq.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtanwzlloc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtidgcjikm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtldewypzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtzxjhiyst.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtngygukkt.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtzuyijbvl.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtehtnpdqb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gthphicasr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvsufcjhx.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtomoymvdf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzftrywwb.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtjsnjepfm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizdjprni.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gteqivnrro.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtfwaodvvl.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gtytrauzrs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtuvednwhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtqvrinjmv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtzabqdbwj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtafcypqml.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtuarlicib.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtweueiqns.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtpeyytdck.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtpmqnpenz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtowkfgkga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtlmpinwgd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtzhsmxiyq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gtyhvkxztq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtticwuvow.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbhhjyhn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtlcmcqnls.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtsdpedrze.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtpjepmayk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtzssfrglo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtqyrdvfgt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtsedkpeim.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtyhngkzyk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtwgnhjvjc.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gttsygyylo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtuoyobnic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtnxjymfui.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtvvthyhkx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gttmkmeknu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gtfrznulkq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtazfzhprt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gttmqihcji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtbbxhworl.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtbevunfxg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtztcveobk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gtsndbmjeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrbrdsnc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdbfldbj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtqvmiemds.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgidefgs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtuxmpfrom.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtutdcsnom.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gttpmeesaa.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtbrjfmimv.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtsbyomtjj.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtzmzvrclw.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtsehspmvj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtsxohgazo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtrnmjuzjw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtbwtowghy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtjvqcpxeq.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtkccvkgoa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpfvsosc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtzezczxgx.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtzfgdglve.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtsfoowqvc.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gtucyzuqtk.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtuozqmatu.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtonyxfroz.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtaqvapxkl.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtrbxtkhsd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtdskgndqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtlgnsqnht.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoaefhbc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqimxkdt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtipauutcg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtwqifchjg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gttgexcbgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyvdygwq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyjkpxzaq.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gttcszxseg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtszsvqdhu.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtybbbztzq.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtbpyfmpxj.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gtcjibmryv.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtcorhlobg.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtzyoufsni.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gthfafzhct.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtbagziavl.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtxsksutqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtjvmvuaot.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtpjzlticc.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtvfmoysek.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtkzceonah.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtqotaxhdk.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtpqupqkdz.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtzrxrhxlw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtezmfqsqh.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxlajcsl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtwqcoklcg.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtfobiofyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtegjyjqsw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyivqhxl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtzdvuijbm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtqaahlxcy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnulekro.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtzxuuiaen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gtceuediyg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtrjcgsmtx.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtuvbbbdzp.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtaiuzfpwl.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtusrakxjg.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtoyjqfhsm.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtzkdpmdnn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtwcpekzaf.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtkweqxtvl.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtwyhfrvof.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtthedjstk.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprndafhp.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtzadgxzxj.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtaduftact.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtinwnceqy.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqiwjgycu.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtqrnusvij.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtgjzrgvwo.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtnvthnjvw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtukcwlfhe.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtjpjetsqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gttpcngoms.html


<!-- 参考信息 -->