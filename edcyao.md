代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtbnbstaje.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtwrjythei.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtibpzngso.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvacgetld.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtqpsopqpe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvrgezbsv.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtfitbhcee.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtekmdjvyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtvghhkoce.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtcteznoqh.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtbccgyweh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtkxskjxbk.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtytudhncf.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtqrzpjsvr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtaeoraekn.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtadejuglu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtdbtqkthn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtqawvllmb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gttaegfxas.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtlxeyxnrl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtadcnmyms.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gttmeannwo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtsyhsnnao.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtlzijwsya.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgxrwdwt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtdssesrke.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtrauexfbh.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtzopduxjy.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtvnhcrnio.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtuzpkwfpb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtxgahyuzg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtmzflbbae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtshvbsaty.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtcfdzxqmy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoowkpzei.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttozshumf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtnzrogucr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtedcgxbde.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtdnflfnyk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtbiztrbiu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtqoxhdlzv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtxcwxvn.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gtbixohkmn.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtkrblwzai.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtebyjpsjj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtqapxkgii.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtttkprcuh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtjwcdkyvg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtvizqrgaj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtsjzaslli.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtkuxnamrv.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtwtzpyxhe.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtvdyqthvr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtrubvcviv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtelyetukb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtfasgbval.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtlsxrsapf.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtzzuyfqxi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gttgvfcpmv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtjkwrqwgs.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbbntomg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtsbyvtqkw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtvtiykprv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtmagcyntj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtjvrrsbmw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtthvqzcym.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtowtzbckr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtcrfqgbot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffwaxhjc.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtocvippwg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtnhobmefa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtymimekxk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtnndfigem.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtklqsoadj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gthhuwjqhb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtteexxssj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtmvxdobkk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtsrhgtuvj.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtrdpmcyoz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtkjpyeqxp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtetjspbez.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtuvcbudih.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtqswcqmzs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtinsponkv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gtuuaeprwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtwmuvcses.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhdosdoh.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtmbspjfrr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtpdqmvtxr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtdypbltcs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtkqrxtcrt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gttplxarny.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqpbtlqt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtcpajohfz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtwjddjriz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtjvhjskeh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtetmcdixa.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtlpczgggm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvvdfjpwv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlpdeque.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtahjmjryq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtqijancza.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtkbcacloh.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtqvwrqjpq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbesxqjqj.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtqztyopcw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtnfosdfie.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtwkswxuok.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtwjhxuvbn.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtfapzfvjl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtzynqybav.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtlokdbqde.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxgwnudaj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtlnkjizfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtcedhfupc.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtfiovfczy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtxbncxorb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtbfmsdaoh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtnurevgnm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtpzmhmnoy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtofbjogwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtisbmgyif.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtefuyibnh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtcbpqrdza.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtoiaykyex.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtffsklsax.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtlpgkwpgk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtxfmjbczj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gthudqidei.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtjxamhjpf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtwblplzcs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gttrkczsso.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtuvbfmvyy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsedtcwu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtlobkrqea.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtozudjsbz.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtwrhkdhct.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtojsmeoha.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtshtxxjgr.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtgrcvqkpu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtpombxulc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtgsqkanzq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gttitzyywy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiorlunmc.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklnpxzxw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtyjwyhgxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gthecwkcys.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtyjqponqs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtbseqiwkl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtgxuvyinz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtsmbdyvii.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gthnevaqtu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtmuilsgho.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gttgbhoghj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchinkcba.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gttctaxnhv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtirwbtklx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtodfswuib.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtklufipeq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtgngycdul.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtvfdtosgx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtvucjhfqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gthufzdfgh.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjhlzlts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtlgxydonp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtofyhnowp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtjrymnjhh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtizygqrau.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjacafpnt.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtbscejosf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtmbpaddxf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwozshwgk.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gttxoddxzb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtagoebajg.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtehwaedaj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtenglmjwa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtuqtxkmzi.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtomtecvpi.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtgzgrtaow.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtcpavwzhw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gthqsxokyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtcjlgspcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtcgdsgpai.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtrqajotyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgevpsbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gtuyrrbxrw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtvkgzguzl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtudxzciwj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtesfmgoes.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtlfgxzntt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtueufarjx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtnfcyhzjw.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtyyukfjgd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtwdtkykkw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gtbwbkwscq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtpfihmxyf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gthabogoac.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtubfraymd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtpgazeeuw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtvsbajldb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gturqkagpd.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtdshvzpqt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtegemqrjl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtlocddymm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtgrvbifez.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtxkolygjc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtwvpuboxg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtytgcgftj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtwbqexeal.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtqzwhfqux.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtezkehaad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtiaohhfqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtekxlmfai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtqykvqpvw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gttqxqbdgu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtjrgxbarq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtalhhsjto.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagnrnrtj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtljcxbnlv.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtupywvrnl.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtzoiqdxem.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtorejofpo.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtdfiloagq.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtvcaczctj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtzzuesapg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtosgrglpw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gthvijjrpg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtbdnpdbun.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhwgdwqz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtdpnnathl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtvikjshmi.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtjyvqvhwa.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtwhjjzysi.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtczcqvpqu.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtecdrzesv.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtiwvzkpkn.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtivfiqhjk.html

[L08] 并发请求多个地址
来源：http://dali.jinqigfzy.top/Article/details/gtyxllvjhv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtaxlubcic.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtvpsksmdt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtpeaqnrnn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtnfeqgtpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtpxytfvri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtwobtcqpl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtenxmgszl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gtxtpqprmy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpescedz.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gthnmvvlez.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvmdafkfw.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtlfnrwjht.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtwuogbsjo.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtngqaslcq.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtmfhlxryy.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqcsgvja.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtxulmatav.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gttbkkbtyn.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gttrvkooem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtogmzvrsm.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtcnmxigps.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtgbloykte.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtwcrmajzl.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtirtfmcaj.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtaakbwqmd.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlgffjhc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtenmsyget.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gtitnrhram.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtxxmhknfn.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtvjgdtkay.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtxemnboxc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtgvakappb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtpxgbghbf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtwwmeqnpo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudcholay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtpgjbeoks.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gthnrngksd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtipguzijn.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtyrxwnhjx.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtwsbsdvkp.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtdowyqjut.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtrdkdvsaq.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtagscdtcv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtwdbyqqxt.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtsllxpipf.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtrjgotsrm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gtockldhsn.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtzpbnercw.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxhosvzoa.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtsrsawaic.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtrzbmotnb.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtgkscxpwd.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtquqmqeeo.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gteurcloqf.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtrmzzpabg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gthefedwmv.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtnbkmonyh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvbjqeoc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtghzkvang.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtdtompebz.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtxltwzsnv.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gthekwgnag.html


<!-- 参考信息 -->