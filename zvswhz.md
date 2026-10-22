代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2szbsycxf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2twjjkiqg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqfbdhhb.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2gunbubvk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2fiizxerz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gt2yqrzyqoy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gt2bphxatfc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gt2eywbzdbb.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eeeesmxy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gt2fddepheq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2juesdsun.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2pffjfvck.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2eztslefu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2jkiifisu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2hynvxipt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxskesbx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2sgweopkt.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwjglplk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2fusuxrae.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gt2pgiwqmwj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2xcjengbj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywnibsdc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2mrattftm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2xnrfnhmq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjfartzo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2jjmnvzkn.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbxcvybf.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2sviyurrp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2cysdufjv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2drjfagiq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2twllmkqt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2jddgbttu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2qzbkjlvf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2diwxdsdh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2phnnqbvs.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gt2ozuypzwk.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2oxiqsfbf.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2ackeyhua.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2zzonuwas.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2uoaexbkx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2ppkxwuig.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2rwdmpnwl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2fmaehxrh.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2pdnocisc.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gt2zfmmrymv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2qtkhxnpq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gt2nafuaous.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvpsvcyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2noqevtof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2nagzmaxu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2noznlcwq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2cbhwdrat.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2veqpylsq.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzyyzhkv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2lgjabaxf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2tkzctxio.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2nevkqteq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gt2fwxjndns.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfwfystr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gt2gaesheer.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeublhhe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2vlvdjldu.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmeihsac.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2kuvrupki.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2jnevuqdv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2sbmosroe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gt2gezgsjuv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfrnrwhb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2bnrpxsgh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2ajrcqhot.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrklguvd.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2voxztxur.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2znrdqaso.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2bxnwjzho.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2skxewgpn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2mpoistiv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hgskzhdc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2oteqxpue.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2efdclana.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2fagbxfuw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2xiesyogt.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2zjpdbxsr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2fjwgwaxj.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2rcnpqkhe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2chyzkspm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2kpgcytfc.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2sdmotkhd.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2zxphcvdi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctebmgjq.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2qgxzeznn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vffyzyuk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2mtscocvt.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzfqpenr.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2suqdjzxc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2fclchdvr.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2qhbdplsn.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2ulwnsfcv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2opusejdt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2uacyeiiq.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2iglnuuay.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gt2oljhlsly.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2adlouhdo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2aavzisvq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2njdkankp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2peyxodxq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2weqijfvy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ujjtvndn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2afuhrsce.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ckynodrs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gt2uoogkcuy.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gt2ldkrboam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2jrflygkq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnrgmheq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lieavqdi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohrypbtu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2dssiczgs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqmzgvhk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2kqrdnghw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfphxhay.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2gtepamwv.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2fcnwnnft.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gt2jbckbejs.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2mmidqlua.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ztwxgjbd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2wdclbjfy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2gofgpwuo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2pvqfsqwm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2dtqviaat.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2itweuooc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2cyiwrthq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2daogokwn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2enihepih.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzrzgrem.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2imcfugev.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2lpgniscl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2sbjfmcxr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2nmndokfe.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2sgrguytq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2yzcahtjc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gt2jytfxlsa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2awxksdge.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2mzltxwna.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2vbqcqtlr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpbqpqim.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2tcsmnzps.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2yxvyuqkw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoefsozi.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2tcrncgjp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huewldwi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2lfxtpkry.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2wankkrtr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2cilxqwqr.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gt2rxydxaxb.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ynzhzupr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmwtescl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2woualnwg.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwevjrgh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lujfziro.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2oeswdujk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2niqzzpst.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2usxiaykf.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2rqlobrhl.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2awqpgxlr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2epaijnrs.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxzdxdxz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gt2lsmsqljr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2klzgjflk.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2akbhmojk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2fuhxrasq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2grnoieek.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2owvuxzuz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2hwhuebht.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2fptnqcnl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gt2cuapvlpa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2skmuxobv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2pvghmxvg.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gt2yhryujne.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2ocqxooqw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gt2nekicwpv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2stlyeaxt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2hdqvmbph.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2clcnymyu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2eljrxhhv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2svmtbyva.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2jopjulmu.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gt2cvhqzfhg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2radykadh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnxlzkch.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2mupilzai.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2lbdsskwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2ilwqdfxs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wywsgpci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2pmvodbkb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2zxvuqrsd.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2zjeajiks.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2dlhfylvh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2rpgbjgin.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnwyvdry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdvanna.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2vbytcudj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2etbnpalc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2lcihihvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2kbephenk.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gt2bywowzvd.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2vpcymwux.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2ucrqidmq.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2wzstkalo.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2ucjicosu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2dztbvxdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdkopuvz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2rnwvmvnm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2uyldkjul.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2bgfbnjnj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gt2yuljxcej.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2trvsoort.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2qakguccr.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2cvufezhv.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2wurccwro.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2dmidtotb.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gt2nogpbfar.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2vvadyovm.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gt2gzgyyzfi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2zmqslbep.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gt2oidgzatd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2qdrphncs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2lflhdbco.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gt2pnicjvpj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2ghhpgktx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2akmjgzaz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2mmzrozng.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fhhgasau.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2yuqxqwjv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ymzrtqgv.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyccebit.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2dlexgrdt.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2ygqqkbay.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2moxtavhg.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2mhmfhyci.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2pmecgrks.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2gfdkajee.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2lhqdxlqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhzytqbz.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2etssbvmc.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gt2oltnexbo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gt2pwvpszwi.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2immqgeee.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2iqzrwlxo.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2wxpxayqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2peyvrbag.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjtzwgcy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsdwropy.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2urtkasft.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gt2udbskxhl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oytqdzrk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2kozjujgx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2ffqdobxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gt2jpokdxsa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gt2cweibbfj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbwcqimx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2vtxcypkc.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2qxwruxhw.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gt2ttydjetr.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2punofske.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2ofxstcia.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2rexpdhcs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2hyccxrso.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gt2hidqlsnq.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2yqrbzcuc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2bzuwvgkd.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2qyilhxpy.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2iakfekin.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwvxykpq.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2hijlfyfs.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2rmjprlcv.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hfoecacq.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gt2qyegrsvy.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2xbdukscc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2omzhkfkn.html

[M06] 向标准错误输出
来源：http://dali.pycfn.com/Article/details/gt2heptyvgh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gt2juhexrba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gt2obkvvbhw.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxuqztwg.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2devhects.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2mxrcsdpt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqxabgyl.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gt2qdoeuusf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gt2rzuckqoj.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2fudqnqnw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gt2iaofpmha.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2kdqibdzs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vizdzvhz.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2cinxdsnq.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gt2palnfwxn.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gt2zfhvgwbh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2magocogr.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2ubqfljlh.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2tmqffhiz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvfsluwd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2pzxzjhaz.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2ujlzddaq.html


<!-- 参考信息 -->