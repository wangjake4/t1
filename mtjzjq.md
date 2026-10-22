代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2wcmysshx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2welygjhx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gt2bfrmtokp.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2czvboewd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2zwselbea.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2imrdwrao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2oawerxnq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spdvuysv.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2esgfsqog.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2nddxzhjl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwxsphmi.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqfompki.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2fiddbpkb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2vvexdyjd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2ukehsrgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2yoohjqes.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnzndjcv.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2qvmxrbmu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2ixlakymm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gt2iebwotum.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2swdonbni.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2iirglzip.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zphhzvfd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2qojmbvhn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2arutsbcl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2nyhrcmfr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfbwovbv.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2ugapwchh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2wvrkcste.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2apkivbnz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnkfuhzk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2usmositv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2soceprkk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gt2dcxxzhyw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2djuxowmt.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2qckivlpr.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2boqtrgnn.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2legebweo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2dgtqgfcp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psfthrig.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjanzmfp.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2gbzywtqh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycetzzex.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqpsuxvb.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2bcgugmus.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2zmunyscq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2syvohucg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssuvuebi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2serzeogf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2ldbdnnuh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qveodidv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2jvyefexu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2eyydipoo.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gt2uwqemwag.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrfrufre.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2almwyviq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2okairrsf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2euulbhtd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2zudmkeap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2lqljqzdm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gt2drvopkkr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2ckeryrdh.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2setafycy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2coraspfo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2yksvhfst.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2jrdcplrd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpytfyqm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2cvnwmdbv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oddtgeyk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbwxdzyt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2tpbjhyqz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2bkqajwee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2usnznbvo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2dvymooos.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tukpauhx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2goapssil.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gt2smchrrsr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2wvphotqq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gt2umtuhjso.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2utgizwft.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnqzeinq.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gt2azqxfzuv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zizpzuyj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xfsvlabf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2gvdtkyky.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2suwxyzcl.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcayohze.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2kfjvrotc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdxqhjrc.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2lfxknouk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gt2eczsogij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iswhtnmt.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gt2vvigbgel.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gt2dbzcojki.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gt2ijogrsfk.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2kgwqbwkv.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2bbcdvavi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2ilyififa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2xdonnzgq.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jscdwrle.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2lzuyfmjh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2xfmmczbl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2qfmkialo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyucspvc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ndteqors.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2tdioildu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gt2dglvkmea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2igxsrxln.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2tcwitrbi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gt2kmqcpdlc.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gt2bqakkubi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnjpmufk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzdpvrya.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2zpfoljwl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2yhsbroaz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2fenvkmeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2qpqbpnrq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2latuldnm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2opbzrwad.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gt2lgxugmwq.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2yrcgjojm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gt2pgzgkdpg.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2jsipwkof.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2uhwvyemr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gt2chnwqahy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2mtrfpspo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gt2jkbcqceg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2rxvincpj.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2ttovxfid.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2fgyhosgq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2rgxmeowr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gt2hzwiyanp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2yjaehjel.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2gfghrxrf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2lscvzerm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2usngomix.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2apfvxkdu.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2rxtzmjxj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2urzscesk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gt2yohothgp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2nektmxow.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2oowsewqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2nvclwtnp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gt2chxhhnmm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2zyxedptc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2febvtuuv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2vsslpjws.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ummuaoho.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2yurrkqxq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2unrgmtpg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2ydfqihwi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gt2iefgexki.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhljsekk.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2yaapyefy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2xfwcaric.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zthpnmys.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gt2dxkuxkgx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2roqhvkfl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrpahg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gt2hershpej.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2rdicptbf.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2uchkvlhr.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbgxplhx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2gjdjajqo.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gt2cggjsedk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxinkj.top/Article/details/gt2lwjltpnm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2cawlvpqn.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2gyxljerv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2xyxuzqmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gt2tbkdmhcm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2vmqcqqyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2aznphzla.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2cocriuxw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2gmflemoz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2guuibvhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gt2djafctao.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2hdwbdpnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxjriyrq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwbilqbd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2rovqvgrq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gt2thtseiob.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2hhojlpqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2pujawnnt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2rldsczzl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbrtqehg.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gt2jfzgrqck.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2jepsyeuc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqxaliv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gt2sinihghc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2yazczynr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2kbrbvadf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gt2lpotdagy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2lpyzfydp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2kflfuwtk.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2uxoanpty.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmllthxs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gt2ufybrupm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2acoqxscv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2qlwothju.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.iojbl.cn/Article/details/gt2hhmgrgyb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gt2hcdevyrm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gt2jzdunogp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2adbfhnor.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2thkpyujf.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2rgtlcvns.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2tlzdezyw.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2apscurdg.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2mejlixii.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqvohqfe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gt2zslcgnqv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kreuikfw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2lodtkgae.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2aszxqmrb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2xucigdwh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcjcctp.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2krggmlvo.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2yphrosxi.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2meaxfgbw.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2bqteboht.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2mfwplhjr.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2zjukvzyw.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2klvefjyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpvzygha.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2nnodttze.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2qtetczgo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2pobrzrvo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2asgtixye.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2rzkgkklo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2vkxrnqti.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbetnmfg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2auqtyoqz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2ulydogqq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kvpwdzti.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2abagifal.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2rnziacba.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2kngircae.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2ldzgpeko.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2vgbawpev.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2hcckiaxi.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gt2gzcqbphi.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gt2autixlmg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2yjmazhvp.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdggffoe.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2zsfappzi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2qdmndflo.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkoduunq.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2kvldjoji.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2jsurtlvh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2oancbcwl.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dotkonyy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kztkenbo.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2wlqctffo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2siqgwqtl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gt2gqohojwc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2mevxlurw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2whdltztq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnlkrwwp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdyvnviv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2qpcbjaal.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2nullpmiz.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2cggmufdt.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2nxyevrpa.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2hvkklhhy.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2lurxyvjd.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijbhuzyn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2xkajlvgc.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gt2bnyexafo.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2qbdobmxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gt2osnfifvy.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gt2itgrwyyo.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2unpwdhgd.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gt2gimnuheh.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arcfpqja.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2qhkwjjrw.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2czxdazti.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ybsrkxwh.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2upjujlip.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gt2cxvuvolj.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2cvuyjkjd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjgkrbdn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gt2sgeoqtnl.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2qnkqhadw.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2yconjmcd.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2lkgsbddw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpksujwd.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gt2fnenjqsv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuxlteqn.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2nokmwscr.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gt2pixuujvc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2wulsainq.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2logembho.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2lvemktiq.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2ovicbpnd.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2veyosbjp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gt2ybgbidhm.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2kgohawtk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2hlibqkne.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gt2nnviulry.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2hwvzwpgt.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2apsmkhrt.html


<!-- 参考信息 -->