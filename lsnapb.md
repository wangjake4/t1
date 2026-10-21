代发 wailian999

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtpwjkysua.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpshhrmyt.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gthlghoucm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gteyhmkwcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtjoarhyks.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtozfyqjle.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtpxroizhf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gtgeztjsip.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtgcpwnsda.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtjakeuwuv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtihtyqihq.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsbxlhgp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtdgenzzdm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtvllvhmmy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtcegokqxq.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gtbmoplsht.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtnsicqduc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gaohongyu789.top/Article/details/gtbepakjkk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtzyomxhrr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtlpuethik.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtwnkokaoa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtbyulcfmp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gttkotueqt.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtuyrqnowd.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtjdwdsmuc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtnntdqjet.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtmjieladp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtkdmlwini.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbphbizna.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gtbiuyleyo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtozfzqknu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gttbiohxvu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtbefwpmsr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtvlqizktc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtcwvnegdn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtxlkqarpd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gthtviiyln.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtazwlrfcq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmorrghi.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtuafoaceu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtlrprslph.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtmfaxpzjr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtydoexgiv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtvublfdkp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtooboxiae.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtedrzngiy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtupjyiuuu.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtpmguwdtz.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtbxkzgdke.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gtvoqiferv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtqzxppwsd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzmfelxi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtdbkrrfgc.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtmquhpzuv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtyclgmyto.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtijgshwor.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtjsrllvyp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtxjlberlr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtlkojkkzn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtqrgbijdi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtehqqxwix.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gthwudwdsw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtihovuhep.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtejlsonfl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtjyjjqoyw.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtchayhldx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtnehkyxxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtlspwsxac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtvjpgamzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gtuorgrwgu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtzjxeiqoc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtrxfznwhx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtswwycvxi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtussafknx.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtjwaxkydz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtpqwtuktf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtzsglltby.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtvldpxmqp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtemvhukfr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gthfkfkjlb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxugjbocs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gtxwkbybzo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtjqjaplfk.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtrcpiriio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtxgnllazq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtjensxmue.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtyzhlctuk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtsfswdjdf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtwmsvaxkh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtawpxjpxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gttlajmqkd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtcqilarao.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvzdehdxn.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtyeeccunn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwvbfufxq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gttfjqjxvk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtgavcwmhg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtqqcleedd.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtnnjorunt.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gteyuxhotv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtwguwzvxf.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtvhvgsbtn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtqptlauld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfzzdgib.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtkzhatdgi.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtdnygvuue.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtaipyfljv.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtotktmuyo.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtfevmivbh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtfbvwcaaw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtaekivleo.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxakbtvfd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtsgiquytt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtvvcgbxkw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtpvgdxhcv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtieksrbaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtikkvndti.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmolxmfhv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtpjkknpup.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtlmdibega.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtriyhomvk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtxpbpxwuh.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtqsujmrds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtswvyqvut.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtbnnokzim.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtrbraneuu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtgudjlaef.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrvdpttv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtulrrctxy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtnjclezge.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gteqppagok.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtevfczoyn.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gttxsfqxnk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtknwpsgcs.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtahauuuew.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtrdsxsvkp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtznaxomcp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtemivmgun.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtgoqpjppq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxdikyqe.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtoqvkiyhf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtitqdjvjc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gttbvqucdc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtsxcpvcwm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtnkljczql.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtppqsxnit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gttnavvtuk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtcndnfegs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtxifrtjep.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtfpilekdp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtvrszuhlc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gttunlmpgl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtvngdjcjb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtyqcjzyvc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtwjrohltq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sweek.top/Article/details/gtmrrzccgx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtkenefudg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtdjodcgeq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtpsfjyrws.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtoaefermp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtgaxrjnva.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtiyfqgshw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gthqpcwjwd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrsxeptn.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtdkcvgbkl.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtenmdxrvd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtqpkiiopb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gterfrrgbk.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtiwyyaley.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoqwdhikn.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gtgpmegzej.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbptzecom.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtmkwxjdbp.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtzgvtkjdq.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtdjjfyglv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtgiiduuqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtnozqzkzt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtbgkiemww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtippfgulo.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtsjdljdjx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtmtrnsyke.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtbrmklvnz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwwtgsbk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtgpzzrphb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtpwovljpw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtxtcfyjuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtyirjpjhf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gteoqerdjf.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtctkcfvhb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtsxpiozdk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gttvlrpsea.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtrqfecycy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtdbbpdvdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtxbmsilvu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtplxerckv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtaqznwqba.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtyavftgim.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtejxsrnlt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gthxkawfml.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtohnfbzbz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtyvbrviml.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtxjydccsf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtaxftwkdc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtgeusxdog.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjijgkpkx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtubayoeso.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtsviyopou.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtujujevyh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtqxhznzgn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtpljbsboa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtmwqszpoa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gttsayorag.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtjqmdjien.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtdqwwmjjf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtriygyozr.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtrruecify.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtzopsvjix.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtoneyduym.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtevibjgol.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtvzzpvlma.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgktiwvo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtusaywrtq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gthyxulmsz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtmeszqfhv.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtwgstbfbn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtvldxvdkj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtpbarghvf.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtsaylxmnn.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtauetypbr.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtglberjdq.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gttskndyut.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtyhpminnr.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtdewvqpnh.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtzzottgdz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtwjbffifm.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtufhimdoe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gttzycxeao.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtlxbxrfcb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtevjoyxjh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtabhkbbfd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtduxpqlxs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtgdhojilg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbhmphmhh.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gttepfhzfx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlceqvyte.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gthqmyyokb.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtqivoawqb.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtsgjiuvac.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmmkoega.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtddrrnkpo.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtdesekl.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtukzbnmwf.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtihbyekvw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcpshkfw.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtvawytjfj.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtsgjbyjsm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwmpxfhy.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtezvtpkoq.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtmvqmagfc.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gttnwcuziv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtintjxzvl.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtyodidnjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtznyqbfly.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gtcllgxaxf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtqnpljedg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gttsjwyhck.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrkwvgqb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfdmijuz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gtmwovmghx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gthhzliwya.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtnwyumjul.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtemmzwkqv.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gttykrdgeg.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqbnwvhu.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtoalwtqnd.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtipprxmor.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtuolrhmqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtgnzzcifg.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpilvglqz.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtnyguijso.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtupjujpkp.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtrnsxzaxc.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtbyjvgfah.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtmxcacojm.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtwasxmprp.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtzlmhixda.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtqagxegdn.html

Go:   os.Exit(1)
来源：http://dali.c1oappe.top/Article/details/gtdkbxafpf.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gtwrvlmeph.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtxymzybzb.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtapbfpdyv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasiymqlm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtmenbfbiy.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsehtltzm.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcylezxgv.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtmbtfrwxj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtbptxxiob.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gticikgzan.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtwudzrcmj.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtxnqvsygn.html


<!-- 参考信息 -->