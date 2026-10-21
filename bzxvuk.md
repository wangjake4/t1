代发 wailian999

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtyrsvuymg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbbslwrzz.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtkwiwsnec.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtjlvtvcwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtktwnpmug.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtrysvxggp.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtijrtgeel.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gtawmqpaun.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtawwmzhod.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtrojsnrxl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtdovipajv.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtqapkufyg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtxvrnltzj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtaypwtyox.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtzuoqivow.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gthkdabdcs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtlnzhrmwv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtnnljyxdz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtvmsfiqpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtfqtsznft.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtlhxmzfmp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtgyvgkiod.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gttmvkvfcv.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxirgbmx.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtipdspbce.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtzmghlaoz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtbxpyjcic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtfkgkypmj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtroefkpod.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtasyaczsh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtcvalzsbx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtzdejhxlp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtfkdtfobs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtwhekkgjb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsnswoay.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtcyokghes.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtovnuwjqn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtmclkpggk.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtvfmmjgza.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtynsnkagc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtfmuxiqns.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtfyeyndqh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtetdaaero.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtnyvddmtq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtxmxhiyti.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtnmaesxop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtzgsevvkl.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtdhhidmfp.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtxgjlwyvr.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtutetjqrg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtslztvsoj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtidgxxiud.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtybcyxpou.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gturcqwpjn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gthgbhisnq.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtqwedqlgb.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtyxvgwoje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtndfwirer.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtoquyvjpk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtniaexrfp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtomuxgqit.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcmsmcxiz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtpwesyfck.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtvorikxlw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtjkelywbf.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtywpxpavm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtnnfwlalf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtcruoejkn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtgelznrmx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gttmckvqbl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtpbbxepge.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gthycbfrna.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtxkbpnnpb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjnxvpot.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtzyjlgpyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtktkqfksu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtpnrcjvkh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtbnhptxck.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gthjfotahb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtmlwqflyg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtgqgszdfn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtfwekwtui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtqlfikrws.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gtefxdcozw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtblxxjvyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtlvbzowlw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtxwjuhaff.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtfgkozudu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkslhklmw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gthftmjyok.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtnrlwagrw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtgwwpgbpk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqdnnrdld.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtrokknhwy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttklutphf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtomqpdrzt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtakirxvbf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtcemixewa.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gttcqzpkhi.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtvuexiqdf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtrjaunhld.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtzjqmukyu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtlojdktxs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtlawdbrby.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtxztknqjw.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtkhadaxye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtudahzplz.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtkmwvepob.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtyxjrablu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtjdxfbltx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtboxtzkxt.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtycofiabq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gticyphivg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtygveqyhk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtsnttlkdv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtaelgnzhj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtvudxmuyr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkbkubar.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtpwztshkk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtgdvrrxqf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gthcjaofov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gthfcklzzw.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gthwuxlfhe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtjfodwmjz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtkwuzgsxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtoaxuoiyd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtfvdgpdet.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtcowbnvsv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtqiwpvuns.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtuaelekxy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtkqndabto.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtwmmivrri.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtyoefkjqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtofsvhjli.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtnjfjqqhb.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtjgqbeqav.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtxrdnjoea.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtywrunabm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqnivltz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtguleoglt.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtowifcgmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtxmuwjcin.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtakgwhqsq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtynzkqjgc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtrnbxylmt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtlqyyhsyq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtbepdpscy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtfcgjqktw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjvzujqvh.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtxrdrfyuz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtxhsejbxb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtuibbuslo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtcvcmolof.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtzwagzfta.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtawtgepwj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtmpkdnucd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gthcqrjnzj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtbxifzefv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtrufwrrwz.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtjtdwlyxc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtzkkadcbh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtajjwykkm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtqaohkhce.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtsevyytjx.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxeuitkq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtvlubshal.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtowefohkr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvuvqsnxu.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtmvvafzeb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkzbnswdi.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtacnnecuu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gthfaykrsx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtonokyfrt.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtpxanpmkp.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtgijrjwcn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtbtjobhme.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtesjatoxe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtddkwkhsb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtlijywabz.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtlczajiut.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtbjgxkyvx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtljzzsqmm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gteznhksty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gteumnffyu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtyabcijlg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtinmjupps.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtgmjlzqfa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtlvothgsx.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtievtdouk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gtxllsbrnf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtoarcslwf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtnaxdcudo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtymvvcdsn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gttqwahvip.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtwrwqfhym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtyhpejecj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gthcawsjib.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtqfgywzfp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtexhxqjum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtjgfzrgpi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtvghinrpb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtluoekjho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtywovofol.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtqquepiti.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gtxcncvuyi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtxhyjhzql.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtlknbmqao.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtipitkarm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtezamutpm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtnvamgxfx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtatjaomui.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtrniyatsp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtzznxmtpc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtuujwqfom.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwqeaxnsp.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gthlnwihpe.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtqhsngbcl.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtokpjysnw.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtvryglvze.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgtniduz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gthbqkpahe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtqcveqhey.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtoxqkhann.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtnnpfjmin.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtbbdfhceu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtdhaqfrha.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtvhldgzud.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtjrdpbbdu.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtagmfsycv.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtzyogxpmg.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtcomfxket.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtoclosmwq.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtzhpqrciv.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtljfyehof.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbxpdcqf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtzlxgsvjg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtmhzmgpzp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtbivmfboy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdscowro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtksarlscs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtxvbznxhj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtbblslvjp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbztvtgsa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtwpftketf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwfqdhtci.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtqmjsuiqb.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtpsjjeprs.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtptkmfedz.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtqxjbbcav.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtyrmlykgj.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtvjhfzupy.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtfvfcsvqc.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtnkpuxvvq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtjyhuasdd.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtykbkdzmn.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtwbtzqpse.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gttwzalzvf.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtdrncqtiy.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtuvxnlxzi.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrrsbvxs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtyfzlnvxx.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gtusmswrzp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtbjprdkby.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtactvgtii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtmmweyqwa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtqetdaywl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtcvhiqdkg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtwbyrvuxw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtcttwtqzw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtrlnivjwh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtpmgaziye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtziobunel.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gtostjiajh.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtdwabygha.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtobemztfq.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gttoifewus.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtghkswksp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gteevtbdei.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gtlmdspxtc.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtkfubychd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gtmjlxytyr.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtbdylmier.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtktkengfe.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gteulilzmq.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmcyfiosp.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuatkrtuw.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtzmcldywp.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtfgwqrjme.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtbapocbks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtsaamzzst.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtxvbxojcr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtkwarryti.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtozrkwdaw.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtiabcuciy.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtmxhpknhb.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtbqwczbmf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gtghocdrop.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtnmnjprew.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtfxnfkcoh.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtpgmtprsi.html


<!-- 参考信息 -->