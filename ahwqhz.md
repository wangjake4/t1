代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gt2vgwhntvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gt2hzyebrej.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2yhvnnnvl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2jccnmggf.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pugsjvib.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2qwscxcwz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gt2vrrpmoxk.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2xfldhdvm.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2eoxyaosm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2wgchlyks.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iducyyqa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2cyucuktp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvbfgggh.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkuqchji.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciqiqdjh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2tfmiilfe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2ioecptew.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gt2saiwmera.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2tsbfxopw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2qqnytfxv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2cnnehcbs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2bfprfqet.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2ilqrszbl.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2msrnyvpu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2ngtvxdcq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2uloskalf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2pyxukkgs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2duxirsyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwvybcvk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2wrvonxnf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2nomgdbbt.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2oibuwkps.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2klaymqou.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2mxdgomhw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gt2zvarsiua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gt2qkhxzxbb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2ubkjbxip.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2vlpemhre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2rypublzf.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2obpoeteg.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gt2oweuuzus.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtxfopeg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2iqitwrhl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2dvsuqdzr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2ncewtsvi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gt2gyekfhcy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2ysbtmwlm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2tapclktu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2tzkytwxx.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2aiqgzuvj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gt2iqcuavku.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2jutvsenl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2diybvjpu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2eqkdhlcd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2ciabpjmi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2ksbrzdho.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gt2cudxxgzb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2rhdwewjw.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gt2avwkutlb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2elywlvdc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2gvclqohy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2wrnctfno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2mrxuctvk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2jkajgywr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2ekzrpvvz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2rigslfeg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2zrkxigjx.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2jtjfslnm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gt2pegcfmlq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2jgiqouju.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2oecrgaij.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2kufimmbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gt2ybnltvip.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2yrmuntmc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2wwojanhu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2rzayobxc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fttzaclr.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gt2uqvchgyr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tmyjnwpw.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gt2suisbhux.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2ytvnwspw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2hrvrcshy.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2yivqduwx.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ilvfoxux.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gt2rsgcechq.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wsmctnni.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2gxecjmkd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2oebaccih.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2luvoiunm.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gt2twoepbkd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gt2vwefgmoo.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2olnvnjwq.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2rrgbditb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jclaaynh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2ltirqlrk.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2uleoywjn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2qcjwyopg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gt2oikmttic.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2yflcaqgr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2atkncmmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2dodabcsx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2syqamhuz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gt2bhozvmph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gt2omyfhcvw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2yhvhlltw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2sxfuvpvm.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjwrfdrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2rfqdmubf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2mcgimwsk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gt2encffpko.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2oqywqrzu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2jqorlsxg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2cgmxgeww.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2klmmgqac.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2eqryyiqd.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gt2hasnahml.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2sflpxcbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2zledzkfp.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2fzxjyact.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ddgxbnxg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gt2jfmcvsyu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2txkjhuqg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2cptoknto.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2ecvaacxe.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2vopazehc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwwdlwwm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2xadocsbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2ezfnucpj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdujdhlt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2binvqrsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2txcqjowv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2umucjmuu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2rutztrvs.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2spvooufo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2xenliqxy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2izhmqhkx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2lgtvghhb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpxasepn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2xfoyrdac.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vormtutz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2xuylgxxe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2buavrbnh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2mdgfiexr.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2gxlpzcga.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2sxnucpwy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2wywzmuyv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwrgfkpe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2zfgkmpbi.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2swxkhyzt.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2eymxusbp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2qdmcldrw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vadidsea.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gt2oyywwzvh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2herfoejf.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2bbtvzxle.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2sweqegut.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2qsdmmxlf.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2rvcikfaw.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjotliam.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gt2ksqqtwbn.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gt2zqonfjwe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2hbxmbano.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2yrsegtmt.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2ouhbejng.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2jzohgpbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywuucgdj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2eoffpjpw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxqauubd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2thpuyily.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gt2pmgpzxik.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gt2albsooqs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqdjoyho.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2aygzxqil.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gt2kqjwulvz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2oyxntwey.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjyhrogw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2tgpsptdv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2smscmjmg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjumyvot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mchlgyds.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gt2ampralzb.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2qmoyybuy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2mrxqswwu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2ntgmxixj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2yspkpwqe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiwpfbuv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gt2htnxbbqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gt2labkbxpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2nzlotsdu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2hscyrnvy.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2kpumemtx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2yfgbwgov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gt2njkkqjrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2pycdnpfb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2bcgbgylm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gt2bhmcpatb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2uxftektj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gt2ghseswkc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2uecmvhfj.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2tgmkodnr.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2lvxltdel.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gt2msblhqzz.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2ezfynizq.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2ngbucvld.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2rzkpfvrr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2sdthsgcl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gt2scxfinkp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2supvmxxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhdnhhdc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2xfdmkeuq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbhtjej.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2ojatiaqr.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2kjgxouhu.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2udaswnlw.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2tgwaakgn.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gt2ahxekoiy.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2kbbubjcj.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2mbbrgdni.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2exkrdyln.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gt2vhohfair.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2fllhvqyj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opztzlcm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2dxomuaaj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gt2ahddxcog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gt2ltibeasy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2lpaxriji.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wyiirbut.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gt2moykoqxc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ypwknshs.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2dmuyqnui.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gt2jlqeidvz.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2gkzotuau.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2sndekmed.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gt2ubueqthb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2yqspmkbm.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2zyfgvfrj.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2sxdalzvn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2hvjbqvio.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2vvdpebnn.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbpxntpr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2rkehijro.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2njhjbpzo.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efgpfbku.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2yikbqten.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2bvtmuptf.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2fclqqhoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2uywuqzze.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2ldebrysx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2bwtlwnay.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2whwrndqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2vnyetuny.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2gwmdarym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2wscgdcqv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gt2rumxhnec.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2ffwzbfmt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2slwmgxfn.html

[M04] 获取当前工作目录
来源：http://dali.fzhhl.top/Article/details/gt2xgwhcbbo.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ctyyzaht.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gt2ffmfaloy.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2dzfiilzz.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2mnenskho.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2hoispjkn.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gt2dllhnmpv.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gt2fmrdbxjy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gt2loiqotmy.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obxmeywn.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2vuabuvnf.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qndsyhnl.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2kkndusch.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ochatdnq.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2byqdckkb.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2fdswwcbc.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2qzkwpcfq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gt2cepsbqlr.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2crlgcmnz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2deqmbslf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2kettmnwp.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2ryrzcjsz.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjzzsous.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2gdvttkfz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eioyxyml.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2kpccxomj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayngkebb.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2ulotabdf.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2bzinyopw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avzykcqh.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2jwtltony.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2vxjqazfp.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2rszorcuk.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2idsxugwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuaviptv.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2zrdcgkpm.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2cydwyunx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gt2cvglbneo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gt2gdgihcbo.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2nhsejosx.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2jlualgdc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gt2gbfzayrf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gt2pomwsszx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2ouiybvjf.html


<!-- 参考信息 -->