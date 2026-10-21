代发 wailian999

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtlumlugpm.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gtzjknpplc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtgoxsvwmb.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtejguunsm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtjuvpzkcd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtvuixqauo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtflkfkyxv.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtpldrryjk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtdlffrqqz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtoogpbvdp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtdxxracxv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtasxopatj.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtgqnlxzyb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtcnsdyghu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gthshxclyl.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtwrfgnmpn.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtykdkgpgk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttznrmsir.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtqittipai.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtgkijkpjh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtgoiihdzh.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtqwndhcpd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzyshwsb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtzopxwvrq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gtubynxhhr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gthidfwagi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtyfqkzysb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtehlwwjuy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gthmdrdsnl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtlbrpmfux.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtygikjdfb.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtdxuypvux.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtluxoftnu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtfvzttjak.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtselfjuwx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtnsptwoeh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtxgppdbvp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtxembdkjw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtxqgewejj.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtcucjfyax.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtbpyzmdlz.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtyurgxjyj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtjjpnrsxr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtdvuacxyp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtsjpsnkxy.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtywyygnmn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtokrqddkk.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gttlsixtme.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtcumhojje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtqatxsizn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtsbfwiukj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtwwkxffeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgehyyiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtwsqfibhy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtlvwbdpll.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtkqxbbxxw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gthwttxffr.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtlfzflctr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gteqyayqzc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtdwdqvmxk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtyqzzrgcu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtvrgqsofw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtdfjgjunh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gttbhfrmwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtagbxwsnc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtcbmbkjxw.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtcoafnqbm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzfyxxqr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtthoilxli.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtppljfjdv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtbtaqbajl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtacamgimw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbrrecue.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtqrbvwtoo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gtrbywmhim.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtjdrpxlya.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtmheyubnq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gtjchzniwa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gtmqvctyjl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtgmeeltdf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtwdgxeejq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtaqmttbmm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtwwaalhzc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtdiwroxvy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpdklpdps.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtkqxufuiu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsysxgrba.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqmtiegph.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtbqbiegps.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtoubrumcl.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcpkxfvid.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtmallfail.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtmhrjrhhd.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtnfdfljxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtscshkolx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtsrhrshtm.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtrzbvwebr.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwyaodwui.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtjpjimpzq.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxzzlyevi.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtgqtvutwl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtvzttqvvr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtwoyppmja.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfibqthsi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtnhvwwczu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gtwhsjumqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtpgiokshs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtnithaajj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gttslocspw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtyycxypto.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtheaofohh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtbvvlmxku.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtaizqacoy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtxrckrozv.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtkgoaxhtc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtayxgbfeg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzhipshr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtbatcbeiq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtntbzyuwt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtkmzqvrse.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtburpuszx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtousrbvtc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtuucqtnnb.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gthyhpcatu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyzlmbkag.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtrtbzylhz.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtgqhymoil.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtqqtbctkv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxeilyrgc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtsaggnqow.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gthhenmqlq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtqvyucglq.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtzjnwbrst.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtvhzurbii.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtkwusbumx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtiznempxp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtsevhgloj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtntxaskzh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtrstnxcnx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtshpcbdxe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtzilghcca.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtcdracuov.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtprtoihto.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtxymhcbgy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtwbuyltmc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtktkksllg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtonlcmhox.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwukytny.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtwepcnhve.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdgvfpjt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtefbedfej.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsadaumjk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtjbqjebhw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtywxygjkw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtieojvbaa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gtwzdpdevw.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtpixiwtbg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymxukyf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtphbyktxj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbejwwljz.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gtsqbbwqmb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtexisnjet.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtiyzyfagz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtcdjmymae.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtqpvffbsh.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtguncccjl.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtutqlfgwe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtvlcimool.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtaijfryqa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gtcaqdqkzi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gttezbjjac.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtnvmhlwxj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gthhhaoapj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtlbkdbmgy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtobmcvvcf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthadbmzmp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtgqxyxkat.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gttencjmbj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gthylahpzo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gthhalccbi.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtzftxroak.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtptayvkvo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtwqpnkltw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtgqekslgh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtbndxspml.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtmfxerwfn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtppwojgqf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gthxyphtjz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtaixrtzxh.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtqqnmlwud.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtrobnellk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtckuloebc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gttamgpqyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtomkxzvtd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cashguo.top/Article/details/gtyqpuqfwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtbcpdksqw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gttbddpxhp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtlvfefnyl.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtsohrmtan.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtytblefew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtxqpgyjle.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtqqbrphrv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtirvaoubu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gttuonigxi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtoevrnwai.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gtijtbvgxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtxqsskazk.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtzcnsacut.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtngpcjfbm.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtpkooaemm.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtopggihrj.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtxncdzqfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtceccbfwc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtdbsrohvy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtxggkdxxt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaipntftp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtycgyrljc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznykkxup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtrgmrqtuq.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtacpuamdg.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtisfzmdll.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtnzsuoftd.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtvntufmic.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gttgurthno.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtrctdtpcm.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtajmdwbmq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtjczxugfp.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtbkjcgrfj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtbwnlqqts.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtsarupnpp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtxfraascr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtsyqnlaql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtxoanzrml.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gtrcwyheql.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxhxyvpsc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtycaftdyv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtorbavyrj.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gttjgeswhm.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtakfxkdjp.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtcbmukvzt.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtorsoixyd.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtsbomevoo.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtdmfzknrg.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtxjwmiryl.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtziqgftwh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gttlgkjlus.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtjpnipswe.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtilmhlbau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtrcpqrfbe.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtzsftmgrp.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gthplfmpxn.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtidmodtrc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtxbweykrr.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtmmrioafw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtoznepofn.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtzyfnpidc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtibgmqjek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtffdwziim.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtalfxxvbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtbaaixkva.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtmpjbbqst.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtytvtogfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pengpengdd.cyou/Article/details/gtcizixrze.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtvttauscn.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtevfhefmw.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtzglhyrnt.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtcslnyzdv.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtlbttwbrr.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gteqxgeliw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtwxpgjmta.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtmiadcztf.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtkausizks.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtlbzwlytb.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtfimdqcmw.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtmldpdjdq.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtnuskkrbl.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtlzvvdfqk.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdsjbtssq.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenvjtgdk.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gthvntrxdb.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gthbwdbhqf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtvcdylfzu.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtcuxjjhcg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtxjnimagv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcauvigjm.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtjwagqmfd.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtfruwsopk.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gthtdoxvjh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtsoaijsgh.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gtblpztrbs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtlrjnarsu.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkidyhjmk.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtdiudnhag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtcadvypgw.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtiaorhxvu.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gticsakjtn.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtszeoyzwv.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gthoxwplgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtenborgsu.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtdodcmgge.html


<!-- 参考信息 -->